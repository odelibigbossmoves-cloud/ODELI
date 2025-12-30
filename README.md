<html lang="en">
  <head>
<meta charset="UTF-8">
<title>ODELI | Official Music Page</title>
<h1>ODELI</h1>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0b0b0b;
  color: white;
}

header {
  background: black;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  letter-spacing: 3px;
  font-size: 24px;
}

nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
  font-size: 14px;
}

section {
  padding: 60px 20px;
  max-width: 1000px;
  margin: auto;
}

.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(180deg, #111, #000);
}

.hero h2 {
  font-size: 48px;
  letter-spacing: 4px;
}

.hero p {
  opacity: 0.7;
}

h2 {
  margin-bottom: 20px;
  letter-spacing: 2px;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}

iframe {
  width: 100%;
  height: 315px;
  border: none;
}

.platform {
  margin-bottom: 40px;
}

.socials a {
  display: block;
  margin: 10px 0;
  color: #aaa;
  text-decoration: none;
}

footer {
  background: black;
  text-align: center;
  padding: 20px;
  margin-top: 60px;
  font-size: 14px;
  opacity: 0.6;
}
</style>
</head>

<body>

<header>
  <h1>ODELI</h1>
  <nav>
    <a href="#music">Music</a>
    <a href="#videos">Videos</a>
    <a href="#socials">Socials</a>
  </nav>
</header>

<div class="hero">
  <h2>ODELI</h2>
  <p>Official Music & Visuals</p>
</div>

<section id="music">

  <div class="platform">
    <h2>Spotify</h2>
    <iframe 
      src="https://open.spotify.com/embed/album/5SQ7C5DuV7c6MJ9XqdNrBw"
      height="380"
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
    </iframe>
  </div>

  <div class="platform">
    <h2>SoundCloud</h2>
    <iframe 
      height="300"
      scrolling="no"
      allow="autoplay"
      src="https://w.soundcloud.com/player/?url=https://soundcloud.com/od3li">
    </iframe>
  </div>

</section>

<section id="videos">
  <h2>YouTube Videos</h2>

  <div class="video-grid">
    <iframe src="https://www.youtube.com/embed/zZU_slM7VME" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/b-bMosv9bIU" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/OTcDlpp--pM" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/SWdsYIklE0o" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/YRf4XSYP3ls" allowfullscreen></iframe>
  </div>

</section>

<section id="socials">
  <h2>Connect</h2>
  <div class="socials">
    <a href="https://instagram.com/od3limusic" target="_blank">Instagram — Music</a>
    <a href="https://instagram.com/delivault" target="_blank">Instagram — Vault</a>
    <a href="https://soundcloud.com/od3li" target="_blank">SoundCloud</a>
    <a href="https://www.youtube.com/@od3li" target="_blank">YouTube</a>
    <a href="https://open.spotify.com/album/5SQ7C5DuV7c6MJ9XqdNrBw" target="_blank">Spotify</a>
  </div>
</section>

<footer>
  © 2025 ODELI — All Rights Reserved
</footer>

</body>
</html>
