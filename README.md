# Rahul-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Profile - Rahul Yadav</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            color: #333;
            background-color: #f4f4f4;
            line-height: 1.6;
        }

        a {
            color: #0078d7;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #ffcc00;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #0078d7, #004a93);
            color: #fff;
            text-align: center;
            padding: 60px 20px;
            border-bottom: 5px solid #004a93;
        }

        header h1 {
            font-size: 3.5rem;
            letter-spacing: 2px;
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .contact-info {
            margin-top: 15px;
            font-size: 1rem;
        }

        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        .image-container {
            text-align: center;
            margin: 20px 0;
        }

        .image-container img {
            max-width: 200px;
            border-radius: 50%;
            border: 5px solid #0078d7;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            animation: fadeIn 1.2s ease;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.8);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        section {
            margin-bottom: 40px;
        }

        section h2 {
            font-size: 2rem;
            color: #0078d7;
            text-transform: uppercase;
            margin-bottom: 20px;
            position: relative;
        }

        section h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background: #0078d7;
            margin-top: 5px;
            margin-left: 5px;
        }

        .section-content {
            padding: 20px;
            background: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        ul {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        ul li {
            background: #fff;
            padding: 15px 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        ul li:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        /* Footer */
        footer {
            background: #004a93;
            color: #fff;
            text-align: center;
            padding: 20px;
            border-top: 5px solid #0078d7;
        }

        footer a {
            color: #ffcc00;
        }

        footer p {
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Rahul Yadav</h1>
        <p>Pursuing Diploma in Software Engineering</p>
        <div class="contact-info">
            <p>Email: <a href="mailto:rahulyadhav09t@gmail.com">rahulyadhav09t@gmail.com</a></p>
            <p>Phone: 8010811744</p>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container">
        <div class="image-container">
            <img src="profile.jpg" alt="Rahul Yadav's Photo">
        </div>

        <section id="about">
            <h2>About Me</h2>
            <div class="section-content">
                <p>I am a motivated fresher with a strong interest in data entry, website development, and shop management. Equipped with a typing speed of 40 WPM, proficiency in Microsoft Excel and Word, and foundational knowledge in HTML, CSS, and JavaScript, I aim to contribute effectively to dynamic and professional environments.</p>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="section-content">
                <ul>
                    <li><strong>Typing Speed:</strong> 40 WPM</li>
                    <li><strong>Microsoft Office:</strong> Excel, Word</li>
                    <li><strong>Web Development:</strong> HTML, CSS, JavaScript</li>
                    <li><strong>Data Organization:</strong> Management and Analysis</li>
                    <li><strong>Problem-Solving:</strong> Analytical Thinking</li>
                </ul>
            </div>
        </section>

        <section id="education">
            <h2>Education</h2>
            <div class="section-content">
                <ul>
                    <li><strong>Diploma in Software Engineering</strong> - [I TECH COMPUTER EDUCATION], Expected Completion: 2025</li>
                    <li><strong>Currently Enrolled:</strong> 11th Grade, Science Stream with a focus on Computer Science</li>
                </ul>
            </div>
        </section>

        <section id="projects">
            <h2>Key Projects</h2>
            <div class="section-content">
                <ul>
                    <li><strong>Responsive Web Design:</strong> Designed modern, responsive static web pages using HTML and CSS.</li>
                    <li><strong>Excel Templates:</strong> Built efficient data entry templates for business use cases.</li>
                </ul>
            </div>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Rahul Yadav. All Rights Reserved. | <a href="mailto:rahulyadhav09t@gmail.com">Contact Me</a></p>
    </footer>
</body>
</html>
