# site-enfants-de-choeurs-de-mfoundi_a_si
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enfants de Chœur – Saint Pierre et Paul</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">✝️</div>
  <h1>Enfants de Chœur</h1>
  <h2>Paroisse Saint Pierre et Paul de Mfoundi_A_Si</h2>
</header>

<nav>
  <a href="#presentation">Présentation</a>
  <a href="#mission">Mission</a>
  <a href="#activites">Activités</a>
  <a href="#galerie">Galerie</a>
  <a href="#contact">Contact</a>
</nav>

<section id="presentation">
  <h3>Présentation</h3>
  <p>
    Nous sommes les enfants de chœur de la paroisse Saint Pierre et Paul de Mfoundi_A_Si.
    Nous servons à l’autel avec foi, discipline et respect.
  </p>
</section>

<section id="mission">
  <h3>Notre mission</h3>
  <ul>
    <li>Servir la messe</li>
    <li>Participer aux célébrations liturgiques</li>
    <li>Grandir dans la foi</li>
    <li>Vivre la fraternité</li>
  </ul>
</section>

<section id="activites">
  <h3>Nos activités</h3>
  <p>
    Messes, répétitions, formations liturgiques, fêtes chrétiennes et activités fraternelles.
  </p>
</section>

<section id="galerie">
  <h3>Galerie</h3>
  <div class="gallery">
    <img src="images/photo1.jpg" alt="Enfants de chœur" class="photo">
    <img src="images/photo2.jpg" alt="Enfants de chœur" class="photo">
    <img src="images/photo3.jpg" alt="Enfants de chœur" class="photo">
  </div>
</section>

<section id="contact">
  <h3>Contact</h3>
  <p>Paroisse Saint Pierre et Paul de Mfoundi_A_Si</p>
  <a class="whatsapp" href="https://wa.me/237620155059" target="_blank">
    📞 Contacter via WhatsApp
  </a>
</section>

<footer>
  <p>© 2025 – Enfants de Chœur</p>
</footer>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f4f4;
}

header {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 20px;
}

.logo {
  font-size: 40px;
}

nav {
  background: #34495e;
  text-align: center;
  padding: 10px;
}

nav a {
  display: inline-block;
  color: white;
  margin: 8px;
  text-decoration: none;
  font-weight: bold;
}

section {
  background: white;
  margin: 15px;
  padding: 20px;
  border-radius: 8px;
}

footer {
  text-align: center;
  background: #2c3e50;
  color: white;
  padding: 10px;
}

/* Bouton WhatsApp */
.whatsapp {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 20px;
  background: #25D366;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 6px;
}

/* Galerie photos */
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.photo {
  width: 100%;
  max-width: 200px;
  border-radius: 8px;
}

/* Responsive téléphone */
@media (max-width: 600px) {
  nav a {
    display: block;
    margin: 10px 0;
  }
}
