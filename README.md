<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Buddy - Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: url('https://i.imgur.com/3ZQ3ZFb.gif') no-repeat center center fixed;
      background-size: cover;
      color: #222;
      scroll-behavior: smooth;
    }#loader {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: #000;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 9999;
}

#loader h1 {
  font-family: 'Orbitron', sans-serif;
  font-size: 28px;
  color: #4CAF50;
  animation: pulseText 1s infinite;
}

@keyframes pulseText {
  0% { opacity: 0.2; }
  50% { opacity: 1; }
  100% { opacity: 0.2; }
}

nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.85);
  padding: 12px 0;
  text-align: center;
  z-index: 1000;
  box-shadow: 0 0 12px #4CAF50;
}

nav a {
  color: #4CAF50;
  margin: 0 18px;
  text-decoration: none;
  font-weight: 600;
  font-family: 'Orbitron', sans-serif;
}

nav a:hover {
  text-shadow: 0 0 10px #4CAF50;
}

section {
  padding: 80px 20px 60px;
  max-width: 750px;
  margin: 90px auto 50px;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 25px;
  box-shadow: 0 0 30px rgba(0, 0, 0, 0.2);
  text-align: center;
  transition: all 0.3s ease-in-out;
}

section:hover {
  transform: scale(1.01);
  box-shadow: 0 0 40px rgba(76, 175, 80, 0.4);
}

h1, h2 {
  font-family: 'Orbitron', sans-serif;
  color: #4CAF50;
  margin-bottom: 10px;
}

.profile-pic {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  border: 4px solid #4CAF50;
  margin-bottom: 20px;
  object-fit: cover;
  animation: pulse 3s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}

iframe {
  width: 100%;
  height: 240px;
  border: none;
  border-radius: 12px;
  margin: 20px 0;
  box-shadow: 0 0 15px #bbb;
}

a.button, button {
  text-decoration: none;
  color: #fff;
  background-color: #4CAF50;
  padding: 12px 25px;
  border-radius: 10px;
  font-weight: bold;
  font-family: 'Orbitron', sans-serif;
  display: inline-block;
  margin: 12px 5px;
  transition: 0.3s;
  border: none;
  box-shadow: 0 0 10px #4CAF50;
}

a.button:hover, button:hover {
  background-color: #45a049;
  transform: scale(1.08);
  box-shadow: 0 0 20px #4CAF50;
}

footer {
  text-align: center;
  padding: 20px;
  color: #fff;
  font-size: 14px;
  background: rgba(0,0,0,0.8);
}

  </style>
</head>
<body>
  <div id="loader">
    <h1>🎮 Loading Ninja World...</h1>
  </div>  <nav>
    <a href="index.html">🏠 Home</a>
    <a href="chat.html">💬 Chat + MiniGame</a>
    <a href="support.html">🌟 Support Me</a>
    <a href="contact.html">📩 Contact</a>
  </nav>  <section id="home" style="display:none">
    <h1>🥷 Welcome to Ninja Gaming</h1>
    <img src="https://i.imgur.com/UoGgU9k.png" alt="Profile" class="profile-pic" />
    <p>I'm Vampire 👻 — your gaming ninja! I post edits, tutorials & fun videos. Join my ninja army now!</p><h2>🔥 Watch My Latest YouTube Video</h2>
<iframe src="https://www.youtube.com/embed/N9Ghy6IT49g" allowfullscreen></iframe>

<h2>📺 My YouTube Playlist</h2>
<iframe src="https://www.youtube.com/embed/videoseries?list=PLnoSfjdGy7ZYM4n5m_EtsFnuOoZ9IKC1y" allowfullscreen></iframe>

<p>
  <a href="https://youtube.com/@sub2vampire" class="button" target="_blank">🔗 Visit My Channel</a>
</p>

<h2>🕹️ My Roblox Profile</h2>
<p><strong>Username:</strong> thesuperboy920</p>
<p><strong>Status:</strong> 🟢 Always Gaming Ninja!</p>

  </section>  <footer>
    © 2025 Your Buddy | Ninja Edition | Designed in Acode with ⚡
  </footer>  <script>
    window.onload = function () {
      document.getElementById("loader").style.display = "none";
      document.getElementById("home").style.display = "block";
    };
  </script></body>
</html>
