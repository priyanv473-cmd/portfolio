# Coding
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Venupriyan S Portfolio</title>

<style>

body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#0f172a;
    color:white;
    scroll-behavior:smooth;
}

/* LANDING PAGE */
.landing{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(to right,#1e3a8a,#2563eb);
}

.landing img{
    width:180px;
    height:180px;
    border-radius:50%;
    object-fit:cover;
    object-position:top;
    border:4px solid white;
    margin-bottom:20px;
}

.landing h1{
    margin-bottom:10px;
    font-size:30px;
}

/* TYPING EFFECT */
.typing{
    font-size:20px;
    margin-bottom:25px;
    overflow:hidden;
    white-space:nowrap;
    border-right:3px solid white;
    width:0;
    animation:typing 3s steps(20,end) forwards, blink 0.7s infinite;
}

@keyframes typing{
    from{width:0}
    to{width:190px}
}

@keyframes blink{
    50%{border-color:transparent}
}

.landing a{
    padding:12px 25px;
    background:white;
    color:#1e3a8a;
    text-decoration:none;
    border-radius:25px;
    font-weight:bold;
}

/* NAVIGATION */
nav{
    background:#1e293b;
    text-align:center;
    padding:15px;
    position:sticky;
    top:0;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 20px;
    font-weight:bold;
}

nav a:hover{
    color:#60a5fa;
}

/* SECTION */
.section{
    padding:70px 40px;
    background:#1e293b;
    border-bottom:1px solid #334155;
}

.section h2{
    color:#60a5fa;
    margin-bottom:15px;
}

/* EDUCATION SKILLS */
.skills-container{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
    margin-top:20px;
}

.skill-box{
    background:#2563eb;
    padding:15px 25px;
    border-radius:8px;
    font-weight:bold;
}

/* ACHIEVEMENTS */
.achievements{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    margin-top:20px;
}

.ach-card{
    background:#334155;
    padding:20px;
    border-radius:10px;
    border-left:5px solid #60a5fa;
}

/* CONTACT */
.contact-box{
    background:#334155;
    padding:25px;
    border-radius:10px;
    max-width:700px;
    word-break:break-all;
}

.contact-box a{
    color:#60a5fa;
    text-decoration:none;
}

.contact-box a:hover{
    text-decoration:underline;
}

footer{
    text-align:center;
    padding:20px;
    background:#0f172a;
}

</style>
</head>

<body>

<!-- FIRST PAGE -->
<div class="landing">
    <img src="profile.jpg.png" alt="Profile Photo">
    <h1>Venupriyan S</h1>
    <div class="typing">I am a BCA Student</div>
    <a href="#home">Explore Me</a>
</div>

<!-- SECOND PAGE NAVIGATION -->
<nav>
    <a href="#home">Home</a>
    <a href="#education">Education</a>
    <a href="#achievements">Achievements</a>
    <a href="#contact">Contact Me</a>
</nav>

<!-- HOME -->
<div class="section" id="home">
    <h2>Home</h2>
    <p>Motivated BCA student passionate about programming and frontend development.</p>
    <p>Strong interest in Java and building responsive web applications.</p>
    <p>Eager to enhance problem-solving skills through real-world projects.</p>
    <p>Quick learner with strong logical thinking ability.</p>
    <p>Interested in modern UI design and clean user experience.</p>
    <p>Good teamwork and communication skills.</p>
</div>

<!-- EDUCATION -->
<div class="section" id="education">
    <h2>Education & Skills</h2>
    <p>Bachelor of Computer Applications (BCA)</p>

    <div class="skills-container">
        <div class="skill-box">Java</div>
        <div class="skill-box">C Programming</div>
        <div class="skill-box">HTML</div>
        <div class="skill-box">CSS</div>
        <div class="skill-box">JavaScript</div>
    </div>
</div>

<!-- ACHIEVEMENTS -->
<div class="section" id="achievements">
    <h2>Achievements</h2>

    <div class="achievements">
        <div class="ach-card">
            <h3>Login Form</h3>
            <p>Responsive login form using HTML & CSS.</p>
        </div>

        <div class="ach-card">
            <h3>Application Form</h3>
            <p>Created structured form with validation design.</p>
        </div>

        <div class="ach-card">
            <h3>Supermarket System</h3>
            <p>Developed basic billing system project.</p>
        </div>

        <div class="ach-card">
            <h3>Cards UI</h3>
            <p>Designed interactive card components layout.</p>
        </div>
    </div>
</div>

<!-- CONTACT -->
<div class="section" id="contact">
    <h2>Contact Me</h2>
    <div class="contact-box">
        <p><strong>Phone:</strong> 
        <a href="tel:9677929158">9677929158</a></p>

        <p><strong>Email:</strong> 
        <a href="mailto:priyanv473@gmail.com">
        priyanv473@gmail.com</a></p>

        <p><strong>GitHub:</strong> 
        <a href="https://github.com/priyanv473-cmd" target="_blank">
        https://github.com/priyanv473-cmd</a></p>

        <p><strong>LinkedIn:</strong> 
        <a href="https://www.linkedin.com/in/venu-priyan-579636377" target="_blank">
        https://www.linkedin.com/in/venu-priyan-579636377</a></p>
    </div>
</div>

<footer>
© 2026 Venupriyan S
</footer>

</body>
</html>

# Website
<img width="1145" height="749" alt="image" src="https://github.com/user-attachments/assets/612d7844-4b7e-4762-86d2-92cb9f0d1e14" />
<img width="1149" height="810" alt="image" src="https://github.com/user-attachments/assets/7e5146d1-80f2-4bca-b01b-18df3f43f47e" />
<img width="1229" height="542" alt="image" src="https://github.com/user-attachments/assets/be5d49ca-f66b-474f-a8ce-bb02f15900ed" />
<img width="1165" height="497" alt="image" src="https://github.com/user-attachments/assets/743a0a77-fc61-41dd-b123-d2d3b134af36" />


# Output
https://priyanv473-cmd.github.io/portfolio/
