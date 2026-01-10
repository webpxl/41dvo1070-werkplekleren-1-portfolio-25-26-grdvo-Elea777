Project: Portfolio — Elea Yildiz

Wat is er gedaan
- Index.html is gerefactord naar semantische en toegankelijke HTML (header, main, sections, footer).
- Bootstrap CSS toegevoegd (CDN) en eigen `style.css` maakt site comic/strip-stijl.
- Drie comic-stijl SVG-afbeeldingen toegevoegd in `fotos/` (project1.svg, project2.svg, project3.svg).
- Hero-foto gebruikt uit `fotos/20250414_132901174_iOS.jpg`.
- `script.js` toegevoegd met een eenvoudige, toegankelijke mobile-menu toggle en ruimte voor uitbreidingen.

Hoe lokaal te testen
1. Open `index.html` direct in je browser door te dubbelklikken (werkt voor statische sites).
2. Of start een eenvoudige server vanuit de projectmap (aanbevolen):

   ```powershell
   # vanuit de projectmap
   python -m http.server 8000
   # Open daarna http://localhost:8000
   ```

Wat je makkelijk kunt aanpassen
- Vervang project-URL's (nu naar example.com) met je eigen links in `index.html`.
- Vervang de hero-foto door een andere in de `fotos/` map (gebruik jpg of webp voor brede browser-ondersteuning).
- Als je .heic hebt: converteer naar .jpg of .webp (gebruik foto-editor of online converter).

Tips voor verder verbeteren (optioneel)
- Voeg echte screenshots of demo-URL's toe voor elke projectkaart.
- Voeg lichte animaties toe in `script.js` (er staat een `initAnimations()` placeholder).

Als je wil dat ik één van de volgende direct uitvoer, zeg het hier:
- Project-links automatisch instellen naar jouw echte URL's.
- .heic naar .jpg/webp conversie (als je het .heic-bestand toevoegt).
- Extra styling of eenvoudige animatie toevoegen (fade-in voor projecten).

Veel succes! Als je iets simpels wilt veranderen, doe ik het meteen voor je.
