# Music-Selling-Website-using-HTML-CSS-JAVA-SCRIPT
Welcome to MusicShop, an immersive online platform designed for music enthusiasts who want a seamless and enjoyable experience when buying and discovering new songs. Developed with a combination of HTML, JavaScript, and CSS.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🎵 MUSIFY</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: url('images/wp11842526-music-playlist-wallpapers.jpg') no-repeat center center fixed;
      background-size: cover;
    }

    nav {
      background-color: #131313; 
      padding: 15px;
      position: fixed;
      width: 100%;
      z-index: 1000;
    }

    .logo {
      font-size: 1.5rem;
      color: #ecf0f1; 
      text-decoration: none;
      text-align: center;
      overflow: hidden; /* Hide overflowing text */
      white-space: nowrap; /* Keep the content on a single line */
      border-right: .15em solid orange; /* The typewriter cursor */
      margin: 0 auto; /* Center the text */
      letter-spacing: .15em; /* Adjust as needed */
      animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
    }

    .nav-links {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: space-around;
      align-items: center;
    }

    .nav-links li {
      margin-right: 20px;
    }

    .nav-links a {
      text-decoration: none;
      color: #ecf0f1; 
      font-weight: bold;
    }

    .hamburger {
      display: none;
      flex-direction: column;
      cursor: pointer;
    }

    .bar {
      width: 25px;
      height: 3px;
      background-color: #ecf0f1;
      margin: 4px 0;
    }

    @media screen and (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        text-align: center;
        width: 100%;
        position: absolute;
        top: 60px;
        background-color: #3498db; 
      }

      .nav-links.show {
        display: flex;
      }

      .nav-links li {
        margin: 10px 0;
      }

      .hamburger {
        display: flex;
      }
    }

    /* The typing effect */
    @keyframes typing {
      from { width: 0px }
      to { width: 10% }
    }

    /* The typewriter cursor effect */
    @keyframes blink-caret {
      from,to { border-color: transparent }
      0% { border-color: rgb(214, 143, 11); }
    }

  </style>
</head>
<body>

  <nav>
    <div class="nav-content">
      <div class="logo">
        <h2>MUSIFY</h2>
      </div>
      <ul class="nav-links">
        <li><a href="Shop.html">Purchase🛒</a></li>        
      </ul>
      <div class="hamburger" onclick="toggleMenu()">
        <div class="bar"></div>
        <div class="bar"></div>
        <div class="bar"></div>
      </div>
    </div>
  </nav>

  <section class="home"></section>
  <div class="text">
   
  </div>

  <script>
    function toggleMenu() {
      const navLinks = document.querySelector('.nav-links');
      navLinks.classList.toggle('show');
    }
  </script>

<style>
    .nav-links a:hover {
    color:  rgb(214, 143, 11);;
}

</style>
</body>
</html>
