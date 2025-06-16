<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tegar Satrio | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f5f7fa;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #1e1e2f, #3f3f60);
      color: white;
      padding: 20px 0;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #1e1e2f;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: 2.8em;
    }

    .hero p {
      font-size: 1.2em;
      margin-top: 10px;
      color: #666;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 12px 24px;
      background: #1e1e2f;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: 0.3s;
    }

    .btn:hover {
      background: #333;
    }

    .section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .section h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2em;
      color: #1e1e2f;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    .project-card h3 {
      margin-bottom: 10px;
      color: #1e1e2f;
    }

    footer {
      background: #1e1e2f;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2em;
      }

      .hero img {
        width: 90px;
        height: 90px;
      }
    }
  </style>
</head>
<body>

<header>
  <nav>
    <a href="#home">Beranda</a>
    <a href="#projects">Proyek</a>
    <a href="#contact" onclick="contact()">Kontak</a>
  </nav>
</header>

<section class="hero" id="home">
  <img src="https://via.placeholder.com/120" alt="Foto Profil" />
  <h1>Tegar Satrio</h1>
  <p>Calon Pengusaha | Web Developer Pemula</p>
  <a href="#projects" class="btn">Lihat Proyek</a>
</section>

<section class="section" id="projects">
  <h2>Proyek Saya</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Landing Page Game</h3>
      <p>Website promo game buatan sendiri. Desain clean, responsif, dan ringan.</p>
    </div>
    <div class="project-card">
      <h3>Website Toko Online</h3>
      <p>Website e-commerce sederhana menggunakan HTML, CSS, dan JS dasar.</p>
    </div>
    <div class="project-card">
      <h3>Portofolio Personal</h3>
      <p>Portofolio online menampilkan skill, proyek, dan kontak saya.</p>
    </div>
  </div>
</section>

<footer>
  &copy; 2025 Tegar Satrio. Dibuat dengan semangat belajar.
</footer>

<script>
  function contact() {
    window.open("https://wa.me/6283187831077", "_blank");
  }
</script>

</body>
</html>
