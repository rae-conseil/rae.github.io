votre-site/
├── index.html (page d'accueil)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAÉ - Réseau d'Accompagnement Éducatif</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">RAÉ</div>
            <ul class="menu">
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="accueil" class="hero">
            <h1>Conseil & accompagnement en éducation spécialisée</h1>
            <p>RAÉ accompagne les établissements médico-sociaux</p>
            <button class="cta-button">Demander un devis</button>
        </section>
    </main>
</body>
</html>

├── style.css (styles)
:root {
    --couleur-principale: #2C5AA0;
    --couleur-secondaire: #F5F5F0;
    --couleur-accent: #D2691E;
    --texte-fonce: #2F2F2F;
}

body {
    font-family: 'Arial', sans-serif;
    color: var(--texte-fonce);
    background-color: var(--couleur-secondaire);
}

.hero {
    background-color: var(--couleur-principale);
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.cta-button {
    background-color: var(--couleur-accent);
    color: white;
    border: none;
    padding: 15px 30px;
    border-radius: 5px;
    cursor: pointer;
}

├── script.js (interactions)
├── images/ (vos photos)
└── pages/
    ├── about.html
    ├── services.html
    └── contact.html
# rae.github.io
