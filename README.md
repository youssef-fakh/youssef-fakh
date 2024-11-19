<!DOCTYPE html>
<html lang="fr">
    <!DOCTYPE html>
    <html lang="fr">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>fashion sphere</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header>
            <h1>FASHION SPHERE</h1>
            <img src="C:\Users\Lilya\OneDrive\Pictures\Screenshots"
            <p>Découvrez des tenues adaptées à votre style personnel</p>
        </header>
    
        <section id="style-selector">
            <h2>Quel est votre style préféré ?</h2>
            <div class="style-option">
                <a href="https://ii.loropiana.com/en/" target="_blank">
                    <p>old money</p>
                </a>
            </div>
            <div class="style-option">
                <a href="https://www.tailorstore.com/fr/fr/guide/style/business-casual-guide" target="_blank">
                    <p>Style Business</p>
                </a>
            </div>
            <div class="style-option">
                <a href="https://www.decathlon.tn/?srsltid=AfmBOoqk4pV43l6hoDy7OfcnicsiA0rBCcsWSD352cs5SaJYGHJFvJRs" target="_blank">
                    <p>Style Sport</p>
                </a>
            </div>
            <div class="style-option">
                <a href="https://www.atode.fr/look-chic/" target="_blank">
                    <p>Style Chic</p>
                </a>
            </div>
        </section>
    
        <section id="style-details" class="hidden">
            <h2>Votre style sélectionné : <span id="selected-style"></span></h2>
            <p id="style-description"></p>
            <button onclick="goBack()">Retour</button>
        </section>
    
        <footer>
            <p>Site créé par votre nom. © 2024</p>
        </footer>
    
        <script src="script.js"></script>
    </body>
    </html>
    
