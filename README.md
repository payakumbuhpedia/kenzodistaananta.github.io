<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Muhammad Kharihal Kenzo | Security Enthusiast</title>

<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#0a0f1c;
color:#fff;
scroll-behavior:smooth;
}

nav{
position:fixed;
width:100%;
background:#000814;
padding:15px;
text-align:center;
z-index:999;
}

nav a{
color:#00bfff;
margin:0 15px;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
text-shadow:0 0 10px #00bfff;
}

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(135deg,#0a0f1c,#001f3f);
}

header h1{
font-size:50px;
color:#00bfff;
text-shadow:0 0 20px #00bfff;
}

header h2{
margin-top:10px;
color:#ccc;
font-weight:300;
}

header p{
max-width:600px;
margin-top:20px;
color:#aaa;
}

section{
padding:80px 10%;
}

h3{
color:#00bfff;
margin-bottom:30px;
text-align:center;
}

.skill{
margin-bottom:20px;
}

.progress{
background:#1c2333;
border-radius:20px;
overflow:hidden;
}

.progress-bar{
height:10px;
background:#00bfff;
width:0;
animation:load 2s forwards;
}

@keyframes load{
from{width:0;}
}

.store-box{
background:#111a2b;
padding:30px;
border-radius:15px;
box-shadow:0 0 20px rgba(0,191,255,0.3);
transition:0.4s;
}

.store-box:hover{
transform:translateY(-10px);
box-shadow:0 0 30px #00bfff;
}

.blog-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.blog-card{
background:#111a2b;
padding:20px;
border-radius:15px;
transition:0.4s;
}

.blog-card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #00bfff;
}

.blog-card h4{
color:#00bfff;
margin-bottom:10px;
}

.social{
text-align:center;
margin-top:20px;
}

.social a{
display:inline-block;
margin:10px;
padding:10px 20px;
border:1px solid #00bfff;
color:#00bfff;
text-decoration:none;
border-radius:20px;
transition:0.3s;
}

.social a:hover{
background:#00bfff;
color:#000;
box-shadow:0 0 20px #00bfff;
}

footer{
text-align:center;
padding:20px;
background:#000814;
color:#777;
}
</style>
</head>
<body>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#store">Store</a>
<a href="#blog">Blog</a>
<a href="#contact">Contact</a>
</nav>

<header>
<h1 data-aos="fade-up">Muhammad Kharihal Kenzo</h1>
<h2 data-aos="fade-up" data-aos-delay="200">Security Enthusiast</h2>
<p data-aos="fade-up" data-aos-delay="400">
Passionate in Cyber Security and Ethical Hacking. Exploring vulnerabilities,
strengthening digital defense, and continuously learning to become better in cybersecurity field.
</p>
</header>

<section id="about" data-aos="fade-right">
<h3>About Me</h3>
<p>
Saya fokus pada Ethical Hacking dan Network Security.
Mengembangkan kemampuan Python, Termux usage, dan Social Engineering awareness
untuk meningkatkan keamanan digital.
</p>
</section>

<section id="skills" data-aos="fade-left">
<h3>Technical Skills</h3>

<div class="skill">
<p>Ethical Hacking</p>
<div class="progress"><div class="progress-bar" style="width:85%"></div></div>
</div>

<div class="skill">
<p>Network Security</p>
<div class="progress"><div class="progress-bar" style="width:80%"></div></div>
</div>

<div class="skill">
<p>Python</p>
<div class="progress"><div class="progress-bar" style="width:75%"></div></div>
</div>

<div class="skill">
<p>Termux</p>
<div class="progress"><div class="progress-bar" style="width:85%"></div></div>
</div>

<div class="skill">
<p>Social Engineering</p>
<div class="progress"><div class="progress-bar" style="width:70%"></div></div>
</div>

</section>

<section id="store" data-aos="zoom-in">
<h3>Digital Store</h3>
<div class="store-box">
<p>
@payakumbuhpedia.store.id adalah digital service store yang berfokus pada layanan boosting media sosial
secara aman, terpercaya, dan profesional dengan dukungan sistem yang stabil.
</p>
</div>
</section>

<section id="blog" data-aos="fade-up">
<h3>Blog</h3>
<div class="blog-grid">

<div class="blog-card">
<h4>Understanding Ethical Hacking</h4>
<p>Basic concept tentang ethical hacking dan pentingnya security testing.</p>
</div>

<div class="blog-card">
<h4>Network Security Basics</h4>
<p>Fundamental jaringan dan cara melindungi sistem dari serangan.</p>
</div>

<div class="blog-card">
<h4>Python for Security</h4>
<p>Bagaimana Python digunakan untuk automation dan security tools.</p>
</div>

</div>
</section>

<section id="contact" data-aos="fade-up">
<h3>Contact</h3>
<div class="social">
<a href="https://instagram.com/kenzodistaananta" target="_blank">Instagram Personal</a>
<a href="https://instagram.com/payakumbuhpedia.store.id" target="_blank">Instagram Store</a>
<a href="https://github.com/kenzodistaananta" target="_blank">GitHub</a>
<a href="mailto:payakumbuhpediastoreid@gmail.com">Email</a>
</div>
</section>

<footer>
© 2026 Muhammad Kharihal Kenzo | Cyber Portfolio
</footer>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
AOS.init();
</script>

</body>
</html>
