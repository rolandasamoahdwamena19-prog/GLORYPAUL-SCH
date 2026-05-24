https://v0-website-clone-sable-nine.vercel.app/
📁 Project Structure
text
glorypaul-school/
├── index.html          (Home page)
├── about.html          (About page)
├── admissions.html     (Admissions page)
├── news.html           (News page)
├── style.css           (Shared styles)
├── script.js           (Slider & interactivity)
└── images/             (Folder for your images – place slider photos here)
1️⃣ index.html – Home Page
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glorypaul School – Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container header-container">
      <div class="logo">
        <img src="images/logo.png" alt="Glorypaul School Crest" style="height: 60px;">
        <h1>GLORYPAUL SCHOOL</h1>
      </div>
      <nav>
        <ul>
          <li><a href="index.html">🏠 Home</a></li>
          <li><a href="about.html">📖 About</a></li>
          <li><a href="admissions.html">📝 Admissions</a></li>
          <li><a href="news.html">📰 News</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Slider -->
  <section class="slider">
    <div class="slide fade">
      <img src="images/slide1.jpg" alt="Students in class">
      <div class="slide-text">Excellence in Every Child</div>
    </div>
    <div class="slide fade">
      <img src="images/slide2.jpg" alt="School playground">
      <div class="slide-text">Moral Values & Leadership</div>
    </div>
    <div class="slide fade">
      <img src="images/slide3.jpg" alt="Graduation ceremony">
      <div class="slide-text">Your Future Starts Here</div>
    </div>
    <a class="prev" onclick="changeSlide(-1)">❮</a>
    <a class="next" onclick="changeSlide(1)">❯</a>
    <div class="dots">
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
      <span class="dot" onclick="currentSlide(3)"></span>
    </div>
  </section>

  <!-- Vision & Mission -->
  <section class="vision-mission container">
    <div class="card">
      <h2>🎯 Our Vision</h2>
      <p>To raise future leaders who excel academically and morally, impacting their communities positively.</p>
    </div>
    <div class="card">
      <h2>⭐ Our Mission</h2>
      <p>To provide holistic education that nurtures intellectual, social, and spiritual growth in a safe environment.</p>
    </div>
  </section>

  <!-- Parent Quote Banner -->
  <section class="quote-banner">
    <div class="container">
      <p>👩‍👧‍👦 <em>"Glorypaul School transformed my child's confidence. The teachers genuinely care!"</em> – Mrs. Asare, Parent</p>
    </div>
  </section>

  <!-- Entrance Exam CTA -->
  <section class="cta">
    <div class="container">
      <h2>📢 Entrance Exams for 2026-2027</h2>
      <p>Limited slots available from Creche to High School. Register now!</p>
      <a href="admissions.html" class="btn">Check Exam Dates →</a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>📍 Location: 15 Education Ridge, Accra, Ghana</p>
      <p>📞 +233 20 123 4567 | ✉️ info@glorypaulschool.edu.gh</p>
      <p>© 2026 Glorypaul School. All rights reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
2️⃣ about.html – About Page
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glorypaul School – About</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container header-container">
      <div class="logo">
        <img src="images/logo.png" alt="Logo" style="height: 60px;">
        <h1>GLORYPAUL SCHOOL</h1>
      </div>
      <nav>
        <ul>
          <li><a href="index.html">🏠 Home</a></li>
          <li><a href="about.html">📖 About</a></li>
          <li><a href="admissions.html">📝 Admissions</a></li>
          <li><a href="news.html">📰 News</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="page-content container">
    <h1>📖 About Glorypaul School</h1>
    <p><strong>Founded in 2012</strong>, Glorypaul School started as a small kindergarten and has grown into a full-fledged institution serving students from Creche through High School. Our campus sits on 5 acres of lush land in Accra, featuring modern classrooms, a science lab, a library, and sports facilities.</p>
    
    <h2>🌟 Our Core Values</h2>
    <ul class="values-list">
      <li>🔹 <strong>Integrity</strong> – We uphold honesty in all we do.</li>
      <li>🔹 <strong>Excellence</strong> – We strive for the highest academic standards.</li>
      <li>🔹 <strong>Respect</strong> – We value every individual.</li>
      <li>🔹 <strong>Service</strong> – We give back to our community.</li>
    </ul>
    
    <h2>📞 Contact & Office Hours</h2>
    <p>📧 Email: info@glorypaulschool.edu.gh<br>
    📞 Phone: +233 20 123 4567<br>
    🕒 Mon–Fri: 8:00 AM – 4:00 PM | Sat: 9:00 AM – 12:00 PM</p>
  </section>

  <footer>
    <div class="container">
      <p>📍 Location: 15 Education Ridge, Accra, Ghana</p>
      <p>📞 +233 20 123 4567 | ✉️ info@glorypaulschool.edu.gh</p>
      <p>© 2026 Glorypaul School</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
3️⃣ admissions.html – Admissions Page
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glorypaul School – Admissions</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container header-container">
      <div class="logo">
        <img src="images/logo.png" alt="Logo" style="height: 60px;">
        <h1>GLORYPAUL SCHOOL</h1>
      </div>
      <nav>
        <ul>
          <li><a href="index.html">🏠 Home</a></li>
          <li><a href="about.html">📖 About</a></li>
          <li><a href="admissions.html">📝 Admissions</a></li>
          <li><a href="news.html">📰 News</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="page-content container">
    <h1>📝 Admissions for 2026-2027</h1>
    <p>We are now accepting applications for the upcoming academic year. Secure your child's place today.</p>
    
    <div class="exam-dates">
      <h2>📅 Entrance Exam Dates</h2>
      <p><strong>📆 June 10 – June 20, 2026</strong><br>Exams are held at our Accra campus from 9:00 AM to 12:00 PM.</p>
      <a href="#" class="btn">Download Application Form</a>
    </div>

    <h2>🏫 Levels Offered</h2>
    <div class="levels-grid">
      <div class="level-card">🍼 Creche (6 months – 2 years)</div>
      <div class="level-card">🎨 KG (3 – 5 years)</div>
      <div class="level-card">📚 Primary (Grades 1–6)</div>
      <div class="level-card">🔬 High School (Grades 7–12)</div>
    </div>

    <h2>📋 Admission Steps</h2>
    <ol>
      <li>Fill out the application form online or at school.</li>
      <li>Submit previous academic records (for Grades 1+).</li>
      <li>Take the entrance exam (dates above).</li>
      <li>Interview with the principal.</li>
      <li>Receive acceptance letter and pay fees.</li>
    </ol>
  </section>

  <footer>
    <div class="container">
      <p>📍 Location: 15 Education Ridge, Accra, Ghana</p>
      <p>📞 +233 20 123 4567 | ✉️ info@glorypaulschool.edu.gh</p>
      <p>© 2026 Glorypaul School</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
4️⃣ news.html – News & Galleries Page
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glorypaul School – News & Events</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container header-container">
      <div class="logo">
        <img src="images/logo.png" alt="Logo" style="height: 60px;">
        <h1>GLORYPAUL SCHOOL</h1>
      </div>
      <nav>
        <ul>
          <li><a href="index.html">🏠 Home</a></li>
          <li><a href="about.html">📖 About</a></li>
          <li><a href="admissions.html">📝 Admissions</a></li>
          <li><a href="news.html">📰 News</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="page-content container">
    <h1>📰 Latest News & Galleries</h1>
    
    <div class="gallery-section">
      <h2>📸 Classroom Activities</h2>
      <div class="gallery">
        <img src="images/class1.jpg" alt="Class activity">
        <img src="images/class2.jpg" alt="Group work">
        <img src="images/class3.jpg" alt="Science experiment">
      </div>
    </div>

    <div class="gallery-section">
      <h2>🇬🇭 Ghana Month Celebrations</h2>
      <div class="gallery">
        <img src="images/ghana1.jpg" alt="Cultural dance">
        <img src="images/ghana2.jpg" alt="Traditional wear">
        <img src="images/ghana3.jpg" alt="Drumming">
      </div>
    </div>

    <div class="gallery-section">
      <h2>💼 Career Day 2026</h2>
      <div class="gallery">
        <img src="images/career1.jpg" alt="Doctor talk">
        <img src="images/career2.jpg" alt="Engineering demo">
        <img src="images/career3.jpg" alt="Student dress-up">
      </div>
    </div>

    <p>📢 For more updates, follow us on social media or visit the school notice board.</p>
  </section>

  <footer>
    <div class="container">
      <p>📍 Location: 15 Education Ridge, Accra, Ghana</p>
      <p>📞 +233 20 123 4567 | ✉️ info@glorypaulschool.edu.gh</p>
      <p>© 2026 Glorypaul School</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
5️⃣ style.css – Shared Styles
css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background-color: #f0f7f0;
  color: #1e2e1e;
}

.container {
  max-width: 1200px;
  margin: auto;
  padding: 0 20px;
}

/* Header */
header {
  background: #2e7d32;
  color: white;
  padding: 1rem 0;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo h1 {
  font-size: 1.5rem;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 1.5rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: 500;
  padding: 0.5rem;
  transition: background 0.2s;
}

nav a:hover {
  background: #1b5e20;
  border-radius: 4px;
}

/* Slider */
.slider {
  position: relative;
  max-width: 100%;
  margin: 0 auto;
  overflow: hidden;
}

.slide {
  display: none;
}

.slide img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

.slide-text {
  position: absolute;
  bottom: 20%;
  left: 10%;
  background: rgba(0,0,0,0.6);
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  font-size: 1.5rem;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 24px;
  transition: 0.3s;
  user-select: none;
  background: rgba(0,0,0,0.5);
}

.prev { left: 0; }
.next { right: 0; }

.prev:hover, .next:hover {
  background: rgba(0,0,0,0.8);
}

.dots {
  text-align: center;
  position: absolute;
  bottom: 15px;
  width: 100%;
}

.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 5px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background 0.3s;
}

.active, .dot:hover {
  background-color: #f9a825;
}

.fade {
  animation: fade 1.5s;
}

@keyframes fade {
  from { opacity: 0.4; }
  to { opacity: 1; }
}

/* Vision & Mission Cards */
.vision-mission {
  display: flex;
  gap: 2rem;
  padding: 3rem 0;
  flex-wrap: wrap;
}

.card {
  flex: 1;
  background: white;
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
  border-top: 6px solid #f9a825;
}

.card h2 {
  color: #2e7d32;
  margin-bottom: 1rem;
}

/* Quote Banner */
.quote-banner {
  background: #f9a825;
  color: #1e2e1e;
  text-align: center;
  padding: 1.5rem;
  font-size: 1.2rem;
  font-weight: 500;
}

/* CTA */
.cta {
  background: #e8f5e9;
  text-align: center;
  padding: 3rem 0;
}

.btn {
  display: inline-block;
  background: #2e7d32;
  color: white;
  padding: 10px 20px;
  border-radius: 30px;
  text-decoration: none;
  margin-top: 1rem;
  font-weight: bold;
  transition: background 0.2s;
}

.btn:hover {
  background: #1b5e20;
}

/* Page Content (About, Admissions, News) */
.page-content {
  padding: 2rem 0;
}

.page-content h1 {
  color: #2e7d32;
  margin-bottom: 1rem;
  font-size: 2rem;
}

.page-content h2 {
  margin: 1.5rem 0 1rem;
  color: #f9a825;
}

.values-list {
  list-style: none;
  margin: 1rem 0;
}

.values-list li {
  margin: 0.5rem 0;
}

.exam-dates {
  background: #e8f5e9;
  padding: 1.5rem;
  border-radius: 16px;
  margin: 1.5rem 0;
}

.levels-grid {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin: 1rem 0;
}

.level-card {
  background: #2e7d32;
  color: white;
  padding: 1rem;
  border-radius: 40px;
  text-align: center;
  flex: 1;
  min-width: 120px;
}

.gallery-section {
  margin: 2rem 0;
}

.gallery {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin-top: 0.5rem;
}

.gallery img {
  width: 200px;
  height: 150px;
  object-fit: cover;
  border-radius: 12px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  transition: transform 0.2s;
}

.gallery img:hover {
  transform: scale(1.02);
}

/* Footer */
footer {
  background: #1b3b1a;
  color: #ddd;
  text-align: center;
  padding: 2rem 0;
  margin-top: 2rem;
}

/* Responsive */
@media (max-width: 768px) {
  .header-container {
    flex-direction: column;
    gap: 1rem;
  }
  nav ul {
    gap: 1rem;
    flex-wrap: wrap;
    justify-content: center;
  }
  .vision-mission {
    flex-direction: column;
  }
  .slide-text {
    font-size: 1rem;
    bottom: 10%;
  }
  .slide img {
    height: 250px;
  }
}
6️⃣ script.js – Slider & Interactivity
javascript
let slideIndex = 1;
showSlides(slideIndex);

function changeSlide(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let slides = document.getElementsByClassName("slide");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) slideIndex = 1;
  if (n < 1) slideIndex = slides.length;
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (let i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  if (slides[slideIndex-1]) {
    slides[slideIndex-1].style.display = "block";
    dots[slideIndex-1].className += " active";
  }
}

// Auto-slide every 5 seconds (optional)
setInterval(() => {
  changeSlide(1);
}, 5000);
🖼️ Required Images (Placeholders)
Create an images/ folder and add these files (you can use your own photos):

logo.png – school crest (height ~60px)

slide1.jpg, slide2.jpg, slide3.jpg – hero slider images (1600x400px)

class1.jpg, class2.jpg, class3.jpg – classroom activities

ghana1.jpg, ghana2.jpg, ghana3.jpg – Ghana month celebrations

career1.jpg, career2.jpg, career3.jpg – career day

If you don’t have them yet, you can temporarily use any royalty‑free images from Unsplash or simply comment out the <img> tags.

🚀 How to Deploy to Your Repository
Create a new folder on your computer called glorypaul-school.

Copy each of the code blocks above into separate files (index.html, about.html, admissions.html, news.html, style.css, script.js).

Create an images folder and add your pictures.

Push the entire folder to your GitHub/GitLab repository.

Connect the repository to Netlify (or any static host) – or open locally with Live Server.

The website will look and function exactly like the live version.

Let me know if you need any modifications (different colours, additional pages, form handling, etc.)!


