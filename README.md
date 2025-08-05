<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f5f5f5;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            background: #444;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 15px;
            display: block;
        }

        nav ul li a:hover {
            background: #555;
        }

        .hero {
            background: #007bff;
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .section h2 {
            margin-bottom: 20px;
            color: #333;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        @media (max-width: 600px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#hero">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="hero">
        <h1>Hello, I'm Nasim</h1>
        <p>Aspiring Web Developer & Creative Thinker</p>
    </section>

    <section class="section" id="about">
        <h2>About Me</h2>
        <p>
            I’m passionate about building simple, clean, and user-friendly websites. This is my basic nasim HTML site to showcase what I can do.
            I love learning new technologies and building fun and useful projects in my free time.
        </p>
    </section>

    <section class="section" id="contact">
        <h2>Contact</h2>
        <p>You can reach me via email at <a href="mailto:your.email@example.com">your.email@example.com</a></p>
    </section>

    <footer>
        &copy; 2025 Nasim Hasan. All rights reserved.
    </footer>

</body>
</html>

