# portfolio
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="profile">
      <img src="profile.jpg" alt="My Photo" />
      <h1>Hello, I'm Saptarshi</h1>
      <p>Aspiring Web Developer</p>
    </div>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>I am passionate about front-end development and design. I enjoy building clean, user-friendly interfaces and bringing ideas to life in the browser.</p>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Weather App</h3>
      <p>A simple weather app using HTML, CSS and JavaScript with API integration.</p>
    </div>
    <div class="project-card">
      <h3>Temperature Converter</h3>
      <p>Converts Fahrenheit to Celsius and vice versa. Great practice for DOM manipulation.</p>
    </div>
  </section>
  <section class="resume">
    <h2>Resume</h2>
    <a href="resume.pdf" download class="resume-btn">Download Resume</a>
  </section>

  <footer>
    <p>Contact me at: <a href="mailto:saptarshi@example.com">saptarshi@example.com</a></p>
    <p>&copy; 2025 My Portfolio</p>
  </footer>
</body>
</html>
style.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fdfdfd;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #2c3e50;
  color: white;
  padding: 2rem 1rem;
  text-align: center;
}

.profile img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 1rem;
  border: 3px solid #fff;
}

.about, .projects, .resume {
  padding: 2rem 1rem;
  max-width: 800px;
  margin: auto;
}

.about h2, .projects h2, .resume h2 {
  color: #2c3e50;
  margin-bottom: 1rem;
  border-bottom: 2px solid #ddd;
  display: inline-block;
}

.project-card {
  background-color: #f2f2f2;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 8px;
}

.resume-btn {
  display: inline-block;
  padding: 0.7rem 1.5rem;
  background-color: #2980b9;
  color: white;
  border-radius: 5px;
  text-decoration: none;
  margin-top: 1rem;
}

.resume-btn:hover {
  background-color: #1c5980;
}

footer {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
