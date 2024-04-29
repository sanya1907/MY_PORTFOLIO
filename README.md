<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<body>
    <header class="header">
        <a href="#" class="logo"><span>Sanya Uppal</span></a>
        <i class='bx bx-menu' id="menu-icon"></i>
        <nav class="navbar">
            <a href="#Home">Home</a>
            <a href="#Education">Education</a>
            <a href="#Skill">Skills</a>
            <a href="#Projects">Projects</a>
            <a href="#Contact">Contact</a>
        </nav>
    </header>
    <section class="Home" id="Home">
        <div class="Home-content">
            <h1>Hi, It's <span>Sanya Uppal</span></h1>
            <h3 class="text-animation">I'm a <span></span></h3>
            <p>
                Passionate individual with a keen interest in machine learning and frontend development. I thrive on
                exploring innovative solutions to complex problems and am constantly seeking to expand my knowledge and
                skills in these fields. With hands-on experience in frontend development, I bring creativity and
                attention to detail to every project I undertake. I am driven by a desire to make a positive impact
                through technology and am always eager to collaborate with like-minded individuals to bring ideas to
                life.
            </p>
            <div class="social-icons">
                <a href="#"><i class='bx bxl-linkedin'></i></a>
                <a href="#"><i class='bx bxl-github'></i></a>
                <a href="#"><i class='bx bxl-instagram-alt'></i></a>
            </div>
            <div class="btn-group">
                <a href="#" class="btn">Hire Me</a>
                <a href="#" class="btn">Contact</a>
            </div>
            <div class="sanya-img">
                <img src="sanya.jpg" alt="My Profile">
            </div>
        </div>
        </div>
    </section>
    <section class="education" id="education">
        <h2 class="heading">Education</h2>
        <div class="timeline-items">
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-data">2020</div>
                <div class="timeline-content">
                    <h3>Secondary Schooling</h3>
                    <p>Completed Secondary education from ICSE board with an aggregate of 94%.</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-data">2021</div>
                <div class="timeline-content">
                    <h3>High School</h3>
                    <p>Completed high school degree in 2021 from CBSE board with an aggregate of 87%.</p>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-data">2022</div>
                <div class="timeline-content">
                    <h3>University</h3>
                    <p>Joined Chandigarh University in 2022 to start my graduation degree for CSE with specialization in
                        Machine Learning and Artificial Intelligence with current SGPA of 8.67</p>
                </div>
            </div>
        </div>
    </section>
    <section class="project">
        <h2 class="heading">PROJECTS</h2>
        <div class="project-container">
            <div class="project-box">
                <div class="project-dot1"></div>
                <div class="project-info">
                    <h4>WEBPAGE DESIGN OF A BABY SHOP</h4>
                    <p>Our website is a haven for all things baby-related. From adorable clothing and essential
                        accessories to educational toys and parenting books,</p>
                </div>
            </div>
            <div class="project-box">
                <div class="project-dot1"></div>
                <div class="project-info">
                    <h4>STOCK PREDICTION AND ANALYSIS</h4>
                    <p>The Stock Analysis and Prediction System is a sophisticated tool designed to analyze historical
                        stock data and predict future price movements. By leveraging advanced algorithms and machine
                        learning techniques, this system provides investors and traders with valuable insights to make
                        informed decisions </p>
                </div>
            </div>
            <div class="project-box">
                <div class="project-dot1"></div>
                <div class="project-info">
                    <h4>EarSkecth- CODE MUSIC WITH PYTHON<h4>

                            <p>EarSketch is a revolutionary platform that allows users to create music using the Python
                                programming language. It seamlessly combines the power of coding with the art of music
                                composition, enabling both beginners and experienced musicians to express their
                                creativity in a unique and innovative way.</p>
                </div>
            </div>
            <div class="project-box">
                <div class="project-dot1"></div>
                <div class="project-info">
                    <h4>NewsAPP using python<h4>
                            <p>This is a GUI based app that provide the current news that is being fetched from NEWSAPI.
                                It includes the welcome page and rating age for the user to submit their review.</p>
                </div>
            </div>
        </div>
    </section>
    <section class="skills" id="skills">
        <h2 class="heading">SKILLS</h2>
        <div class="skills-box">
            <div class="inside-box"></div>
            <h2 class="heading"></h2>
            <div class="wrapper">
                <div class="skills-set">
                    <h2>C++</h2>
                    <div class="level"> </div>

                </div>
                <div class="skills-set">

                    <h2>PYTHON</h2>
                    <div class="level">
                    </div>
                </div>
                <div class="skills-set">
                    <h2>JAVA</h2>
                    <div class="level"></div>
                </div>
                <div class="skills-set">
                    <h2>HTML</h2>
                    <div class="level"></div>
                </div>
                <div class="skills-set">
                    <h2>CSS</h2>
                    <div class="level"></div>
                </div>
                <div class="skills-set">
                    <h2>Machine Learning</h2>
                    <div class="level"></div>
                </div>
    </section>
<section class="contact" id="contact" >
    <h2 class="heading">Contact <span>ME</span></h2>
    <form action="">
        <div class="input-group">
            <div class="input-box">
                <input type="text" placeholder="FULL NAME">
                <input type="email" placeholder="E-MAIL">
            </div>
            <div class="input-box">
                <input type="number" placeholder="PHONE-NUMBER">
                <input type="text place" placeholder="Subject">
            </div>
        </div>
        <div class="input-group-2">
            <textarea name="" id="" cols="30" rows="10" placeholder="Your Message please!!"></textarea>
            <input type="submit" value="Send Message" class="btn">
        </div>
    </form>
</section>
<footer class="footer">
    <div class="social">
        <a href="#"><i class='bx bxl-linkedin'></i></a>
        <a href="#"><i class='bx bxl-github'></i></a>
        <a href="#"><i class='bx bxl-instagram-alt'></i></a>
    </div>
<ul class="list">
    <li>
        <a href="#">FAQ</a>
    </li>
    <li>
        <a href="#">About Me</a>
    </li>
    <li>
        <a href="#">Skills</a>
    </li>
    <li>
        <a href="#">Projects</a>
    </li>
    <li>
        <a href="#">Contact</a>
    </li>
    <li>

    </li>
</ul>
<p class="copyright">
    &copy Sanya Uppal | All Rights Reserved
</p>
</footer>
    <!-- <script src="script.js"></script> -->
</body>

</html>
