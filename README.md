<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #6495ED;
      color: black;
    }
    nav {
      background-color: #F0F8FF;
      color: F0FFFF;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav h1 {
      margin: 0;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    nav ul li {
      font-weight: bold;
    }
    nav ul li a {
      color: F0FFFF;
      text-decoration: none;
    }
    .container {
      text-align: center;
      padding: 40px;
    }
    img {
      width: 300px;
      height: 300px;
      border-radius: 50%;
      object-fit: cover;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <nav>
    <h1>About Me</h1>
    <ul>
      <li><a href="#">Educational Background</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">RevGuard Team</a></li>
    </ul>
  </nav>

  <div class="container">
    <h2><i>Welcome to My Website<i></h2>
    <p>Hi, my name is Ashley Crezyl Almozara. I’m 22 years old, born on November 13, 2002, and I live in Bacoor City Cavite.<p> 
	<p>I am currently a third-year student taking up Bachelor of Science in Information Technology at Cavite State University – CCAT Campus. <p>
	<p>Alongside my studies, I work part-time as a service crew member at McDonald’s, where I continue to build my skills in customer service and time management.</p>
    <p><strong>HOBBIES:</strong><br>
      Cooking<br>
      Traveling<br>
	  Gardening<br>
      Watching movies<br>
      Listening to music<br>
    </p>
    <img src="ash.jpg" alt="My Photo">
  </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Educational Background</title>
  <link rel="stylesheet" href="style.css">
  <style>
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f6ff;
  color: #333;
  padding-bottom: 50px;
}


header {
  background-color: #5f9ea0;
  color: white;
  padding: 20px;
  text-align: center;
  position: relative;
}

nav {
  position: absolute;
  top: 20px;
  right: 30px;
}

nav a {
  margin-left: 20px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}


main {
  max-width: 800px;
  margin: 40px auto;
  padding: 0 20px;
}

.card {
  background: #ffffff;
  border: 2px solid #b2d3f2;
  border-radius: 16px;
  padding: 25px;
  margin-bottom: 30px;
  box-shadow: 0 6px 12px rgba(0, 128, 255, 0.1);
}

.card h2 {
  color: #2a75bb;
  margin-bottom: 15px;
  font-size: 1.5em;
}

.card p {
  margin-bottom: 10px;
  line-height: 1.6;
}


footer {
  text-align: center;
  margin-top: 30px;
  font-size: 14px;
}

footer a {
  color: #ff69b4;
  text-decoration: none;
  font-weight: bold;
}

footer a:hover {
  text-decoration: underline;
}
</style>
</head>
<body>
  <header>
    <h1>Educational Background</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Projects</a>
    </nav>
  </header>

  <main>
    <section class="card">
      <h2>🎓 Bachelor of Science in Information and Technology</h2>
      <p><strong>Institution:</strong> Cavite State University CCAT Campus</p>
      <p><strong>Year:</strong> 2022 - Present</p>
      <p><strong>Location:</strong> Rosario, Cavite</p>
    </section>

    <section class="card">
      <h2>💻 TVL Information Communication and Technology</h2>
      <p><strong>Institution:</strong> Theresian School Of Cavite</p>
      <p><strong>Year:</strong> 2019 - 2021</p>
      <p><strong>Location:</strong> Habay 1, Bacoor City, Cavite</p>
      <p><strong>Details:</strong> Graduated with honors.</p>
    </section>
  </main>

  <footer>
    <p>Contact me at <a href="mailto:almozaraashley220@gmail.com">almozaraashley220@gmail.com</a></p>
  </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Projects</title>
  <style>
    /* Reset & Fonts */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0f4ff; /* Light pastel blue */
      color: #2c3e50;
    }

    /* Navigation Bar */
    nav {
      background-color: #8bbfe0;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    nav h1 {
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
      transition: opacity 0.3s;
    }

    nav a:hover {
      opacity: 0.85;
    }

    /* Page Content */
    .container {
      text-align: center;
      padding: 50px 20px;
    }

    .container h2 {
      font-size: 2.5rem;
      color: #3b4b7c;
      margin-bottom: 10px;
    }

    .container p {
      font-size: 1.1rem;
      color: #5d6d7e;
      margin-bottom: 40px;
    }

    /* Projects Grid */
    .projects {
      display: flex;
      justify-content: center;
      gap: 25px;
      flex-wrap: wrap;
      padding: 0 30px;
    }

    .projects a {
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 6px 15px rgba(139, 191, 224, 0.4);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .projects a:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 20px rgba(139, 191, 224, 0.6);
    }

    .projects img {
      width: 250px;
      height: 160px;
      object-fit: cover;
      display: block;
      border-radius: 20px;
    }
  </style>
</head>
<body>

  <nav>
    <h1>Personal Projects</h1>
    <div>
      <a href="index.html">Home</a>
      <a href="education.html">Educational Background</a>
    </div>
  </nav>

  <div class="container">
    <h2>My Projects</h2>
    <p>Click each box to view more details ✨</p>

     <div class="projects">
      <a href="https://github.com/shleyxx/Array.java"target="_blank">
      </a>
      <a href="https://github.com/shleyxx/MultiplicationTable"target="_blank">
      </a>
      <a href="https://github.com/shleyxx/Library"target="_blank">
      </a>
	  <a href="https://github.com/shleyxx/Integers"target="_blank">
      </a>
	  <a href="https://github.com/shleyxx/Ascending "target="_blank">
      </a>
	  <a href="https://github.com/shleyxx/Palindrome"target="_blank">
      </a>
	   <a href="https://github.com/shleyxx/Basic-HTML"target="_blank">
      </a>
	   <a href="https://github.com/shleyxx/Age-Generator"target="_blank">
      </a>
	   <a href="https://github.com/shleyxx/Simple-Registration"target="_blank">
      </a>
    </div>
  </div>

</body>
</html>
