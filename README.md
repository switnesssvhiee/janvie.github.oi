<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            background-color: #444;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 20px;
        }
        .projects, .skills, .contact {
            margin-bottom: 40px;
        }
        .project-item {
            margin-bottom: 20px;
        }
        .skills-list {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About Section --
    <section id="about" class="container">
        <h2 class="section-title">About Me</h2>
        <p>Hi, I am Serrada, Janvie B. a passionate [Your Profession/Title] with expertise in coding . I have worked on various projects that demonstrate my abilities in [Field of Expertise].</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container">
        <h2 class="section-title">Projects</h2>
        <div class="project-item">
            <h3>Project 1: [Portfolio Website]</h3>
            <p>Description of the project. What you worked on, the technologies used, and the outcome of the project.</p>
        </div>
        <div class="project-item">
            <h3>Project 2: [Social Media Analytics Tool]</h3>
            <p>Description of the project.
Overview: Developed a comprehensive analytics tool that tracks and analyzes key metrics across multiple social media platforms, helping businesses monitor their performance, audience engagement, and trends over time.

Role: Lead Developer – I was responsible for designing the database schema, implementing data scraping mechanisms, and developing the user dashboard for real-time analytics.

Technologies Used: Python (for web scraping), JavaScript (React for front-end), Node.js (back-end API), MongoDB (database), D3.js (for data visualization).

Outcome: The tool was successfully deployed and adopted by several businesses, allowing them to reduce manual data collection time by 70% and improve their social media strategy by identifying key trends and insights in audience behavior. It enabled the users to visualize data from multiple platforms such as Twitter, Instagram, and Facebook in a single dashboard, providing real-time insights and performance tracking.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="container">
        <h2 class="section-title">Skills</h2>
        <ul class="skills-list">
            <li>GYM</li>
            <li>COOKING</li>
            <li>CODING OTHER</li>
            <li>React</li>
            <li>READING</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2 class="section-title">Contact Me</h2>
        <p>Email: janvieserrada@gmail.com</p>
        <p>Phone: 09107445594</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>

</body>
</html>
