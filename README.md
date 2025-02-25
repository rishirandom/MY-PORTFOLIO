MY PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rishi Ranjan's Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #3498db;
            --secondary: #e74c3c;
            --accent: #2ecc71;
            --dark: #2c3e50;
            --light: #ecf0f1;
        }

        body {
            background: linear-gradient(135deg, #f5f6fa 0%, #dcdde1 100%);
            color: var(--dark);
        }

        .navbar {
            position: fixed;
            width: 100%;
            padding: 1rem;
            background: rgba(255, 255, 255, 0.9);
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            z-index: 1000;
        }

        .nav-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--accent);
            transform: translateY(-2px);
        }

        .hero {
            padding: 150px 2rem 100px;
            text-align: center;
            background: linear-gradient(45deg, #8e44ad, #3498db);
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .section {
            padding: 4rem 2rem;
            text-align: center;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .tech-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .tech-card:hover {
            transform: translateY(-10px);
        }

        .project-card {
            background: white;
            margin: 2rem auto;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            max-width: 800px;
        }

        .contact-section {
            text-align: center;
            padding: 4rem 2rem;
            background: linear-gradient(45deg, #e74c3c, #e67e22);
            color: white;
        }

        .button {
            padding: 1rem 2rem;
            border-radius: 50px;
            background: var(--accent);
            color: white;
            text-decoration: none;
            display: inline-block;
            margin-top: 1rem;
            transition: all 0.3s ease;
        }

        .button:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .nav-links {
                gap: 1rem;
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="nav-links">
            <a href="#about">About</a>
                        <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section class="hero">
        <h1>Rishi Ranjan</h1>
        <p>Welcome to My Portfolio</p>
        <p>Passionate Developer | Python | SQL | Ruby | Java</p>
    </section>

    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
            I am a Python developer and Data scientist with a passion for creating innovative solutions. 
            I have experience in various programming languages and frameworks, and I love 
            tackling challenging problems. My goal is to leverage technology to make a 
            positive impact.
        </p>
    </section>

    <section id="skills" class="section">
        <h2>Skills</h2>
        <div class="tech-grid">
            <div class="tech-card">
                <h3>Python</h3>
                <p>Expert in Python programming, working with "PANDAS" , "SMTP" and many other projects using python.</p>
                <a href="https://www.python.org/" class="button" target="_blank">Learn More</a>
            </div>
            <div class="tech-card">
                <h3>SQL</h3>
                <p>Proficient in SQL for database management and data analysis.</p>
                <a href="https://www.mysql.com/" class="button" target="_blank">Learn More</a>
            </div>
            <div class="tech-card">
                <h3>Ruby</h3>
                <p>Experienced in Ruby on Rails for building web applications and made ai chatbot using Ruby. </p>
                <a href="https://www.ruby-lang.org/en/" class="button" target="_blank">Learn More</a>
            </div>
            <div class="tech-card">
                <h3>Java</h3>
                <p>Skilled in Java for building  applications, coding and using java tools for programming.</p>
                <a href="https://www.oracle.com/java/technologies/javase-jdk11-downloads.html" class="button" target="_blank">Learn More</a>
            </div>
            <div class="tech-card">
                <h3>PHP</h3>
                <p>A highly skilled PHP developer with expertise in building dynamic, scalable web applications. Proficient in writing clean, efficient, and well-documented PHP code.</p>
                <a href="https://www.oracle.com/java/technologies/javase-jdk11-downloads.html" class="button" target="_blank">Learn More</a>
            </div>
        </div>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>My Portfolio </h3>
            <p>
              I designed and developed a personal portfolio website to showcase my skills, projects, and experience. The website was built using technologies such as HTML, CSS, JavaScript, and Ruby, ensuring a dynamic and interactive user experience. I implemented a responsive and visually appealing interface using AI tools and CSS, making the site accessible across different devices. Additionally, I integrated GitHub for version control, streamlining the development process and maintaining code efficiency. This portfolio serves as a professional platform to highlight my completed projects, technical skills.
            </p>
            
        </div>
        <div class="project-card">
            <h3>AI-Powered Inventory Management</h3>
            <p>
                A Python-Programmer, I've gained hands-on experience in automating workflows with SMTP, data manipulation using Pandas, and managing large datasets. My role includes working with JSON for seamless data exchange, utilizing HTML for web development, and optimizing file systems for efficient storage and retrieval. Additionally, I contribute to blogging by creating and managing content to boost digital engagement. These projects have strengthened my technical skills and problem-solving abilities in real-world applications.
            </p>
            
            
           
        </div>

        <div class="project-card">
            <h3>Backend Web-Designing for motorbikes </h3>
            <p>
                A Java application This project highlights the ability to build a full-fledged backend system for an e-commerce platform, ensuring smooth product browsing, user management, and secure transactions in the motorcycle industry.
            </p>
            
        </div>

        <div class="project-card">
            <h3>E-commerce Platform</h3>
            <p>
                A Ruby on Rails application that serves as a marketplace with real-time bidding 
                features. This project demonstrates the use of ActionCable for WebSocket support.
            </p>
            
        </div>

        <div class="project-card">
            <h3>Data Analysis and working with excels files </h3>
            <p>
                A SQL-based dashboard that visualizes sales data and trends using Python's 
                Pandas and Matplotlib libraries. This project helps businesses make data-driven 
                decisions.
            </p>
            </div>
         <div class="project-card">
           <h3>Logos and QR code. </h3>
           <p>
             I utilized Python to create a unique custom logo and generate a scannable QR code. The logo was crafted using Python's Pillow (PIL) library for image manipulation, while the qrcode library was employed to generate a dynamic, interactive QR code, linking users to a specific website or application. This project showcases the integration of creativity with programming to develop personalized branding elements.
                    
           </p>
          
        </div>
        <div class="project-card">
           <h3>PHP Projects </h3>
           <p>
             Successfully developed and deployed multiple web applications using PHP, focusing on building dynamic, user-friendly websites and custom CMS solutions. 
             These projects involved utilizing PHP frameworks like Laravel and CodeIgniter, along with MySQL for database management. 
           </p>
        </div>
    </section>
     </section>

            </div>
        <section id="projects" class="section">
        <h2>CHECK IT OUT </h2>
        <div class="project-card">
            <h3>My GitHub Projects </h3>
            <p>
              <a href="https://rishirandom.github.io/MYPORTFOLIO/" class="button" target="_blank">GITHUB</a>
              <a href="https://rishirandom.github.io/LOGO/" class="button" target="_blank">GITHUB</a>

              </p>
            
            
        </div>
            

    <section id="contact" class="contact-section">
        <h2>Contact Me</h2>
        <p>If you would like to get in touch, feel free to reach out!</p>
        <p>
            <i class="fas fa-phone"></i> 
            <a href="tel:8609696428" style="color: white;">+91 86096 96428</a>
        </p>
        <p>
            <i class="fas fa-envelope"></i> 
            <a href="mailto:rishiranjangtk@gmail.com" style="color: white;">rishiranjangtk@gmail.com</a>
        </p>
        <div style="font-size: 2rem;">
            <a href="https://www.linkedin.com/in/rishi-ranjan-7984a134a/" target="_blank" style="color: white; margin: 0 1rem;">
                <i class="fab fa-linkedin"></i>
          
            </a>
            
        </div>
    </section>

    <footer style="text-align: center; padding: 2rem; background: var(--light);">
        <p>&copy; 2023 Rishi Ranjan. All rights reserved.</p>
    </footer>
</body>
</html>
