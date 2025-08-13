# MS-Design-Sattlerei-
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MS Design Sattlerei</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
        }
        header {
            background: linear-gradient(135deg, #222, #444);
            color: white;
            padding: 2em;
            text-align: center;
        }
        nav {
            background: #111;
            text-align: center;
            padding: 0.5em;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }
        nav a:hover {
            color: #ffd700;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 20px 0;
        }
        section {
            background: white;
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        h2 {
            border-left: 5px solid #ffd700;
            padding-left: 10px;
            margin-bottom: 15px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li::before {
            content: "✔️";
            margin-right: 10px;
        }

        /* Galerie Grid */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .gallery-grid img {
            width: 100%;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .gallery-grid img:hover {
            transform: scale(1.05);
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 15px;
        }
        /* WhatsApp Button */
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 20px;
            right: 20px;
            background-color: #25d366;
            color: white;
            border-radius: 50%;
            text-align: center;
            font-size: 30px;
            z-index: 100;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }
        .whatsapp-float i {
            margin-top: 15px;
        }

        /* Google Translate Fixed Button */
        .translate-top-right {
            position: fixed;
            top: 10px;
            right: 10px;
            z-index: 999;
            background: #f0f0f0;
            padding: 5px 10px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>

    <!-- Google Translate Widget -->
    <div id="google_translate_element" class="translate-top-right"></div>
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({
                pageLanguage: 'de',
                includedLanguages: 'de,en,ar,fr',
                layout: google.translate.TranslateElement.InlineLayout.SIMPLE
            }, 'google_translate_element');
        }
    </script>
    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

    <header>
        <h1>MS Design Sattlerei</h1>
        <p>Qualität, Komfort und Stil – Seit über 50 Jahren Meisterarbeit</p>
    </header>

    <nav>
        <a href="#about">Über uns</a>
        <a href="#services">Dienstleistungen</a>
        <a href="#gallery">Galerie</a>
        <a href="#contact">Kontakt</a>
    </nav>

    <div class="container">

        <section id="about">
            <h2>Über uns</h2>
            <p>MS Design Sattlerei ist ein Familienunternehmen mit über 50 Jahren Erfahrung in der Fahrzeug- und Motorradsattlerei. 
               Unser Meister verbindet traditionelle Handwerkskunst mit modernem Design, um jedes Projekt mit höchster Präzision und Sorgfalt umzusetzen.  
               Wir legen größten Wert auf <strong>Qualität, Komfort und exzellenten Kundenservice</strong> – die Zufriedenheit unserer Kunden steht bei uns an erster Stelle.  
               Neben Fahrzeugen und Booten polstern wir auch <strong>Sofas und Wohnmöbel</strong> neu und verleihen ihnen ein frisches, individuelles Aussehen.  
               Wir freuen uns besonders, wenn unsere Kunden mit eigenen Ideen oder speziellen Designwünschen zu uns kommen – 
               denn wir setzen diese mit Begeisterung und handwerklicher Perfektion um.</p>
        </section>

        <section id="services">
            <h2>Dienstleistungen</h2>
            <ul>
                <li>Autosattlerei – Sitze, Türen, Dachhimmel</li>
                <li>Motorradsitzbänke neu polstern und beziehen</li>
                <li>Bootspolsterung & Innenausstattung</li>
                <li>Verdecke für Cabrios anfertigen und montieren</li>
                <li>Lenkräder & Armaturenbretter beziehen</li>
                <li>Restaurierung von Oldtimer-Innenräumen</li>
                <li>Sofas & Wohnmöbel neu polstern</li>
                <li>Individuelle Designanfertigungen nach Kundenwunsch</li>
            </ul>
        </section>

        <section id="gallery">
            <h2>Galerie</h2>
            <div class="gallery-grid">
                <img src="https://via.placeholder.com/400x300?text=Vorher+1" alt="Vorher">
                <img src="https://via.placeholder.com/400x300?text=Nachher+1" alt="Nachher">
                <img src="https://via.placeholder.com/400x300?text=Werkstatt" alt="Werkstatt">
                <img src="https://via.placeholder.com/400x300?text=Vorher+2" alt="Vorher">
                <img src="https://via.placeholder.com/400x300?text=Nachher+2" alt="Nachher">
                <img src="https://via.placeholder.com/400x300?text=Werkstatt+2" alt="Werkstatt">
            </div>
        </section>

        <section id="contact">
            <h2>Kontakt</h2>
            <p><strong>Adresse:</strong> Hauptstraße 54, 88138 Sigmarszell</p>
            <p><strong>Telefon:</strong> +49 176 80004350</p>
            <p><strong>E-Mail:</strong> ms.design.sattlerei@gmail.com</p>
            <p><strong>Instagram:</strong> <a href="https://www.instagram.com/ms_design_sattlerei?igsh=MW5wMnhybzVtODM2" target="_blank">Besuchen Sie uns</a></p>
            <p><strong>Öffnungszeiten:</strong><br>
               Montag – Freitag: 09:00 – 18:00<br>
               Samstag: 10:00 – 16:00
            </p>
        </section>

    </div>

    <footer>
        <p>© 2025 MS Design Sattlerei - Alle Rechte vorbehalten</p>
    </footer>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/4917680004350" class="whatsapp-float" target="_blank">
        <i>💬</i>
    </a>

</body>
</html>
