B-IV LernApp – PWA
====================

Enthält alle 82 aus der Excel-Datei extrahierten Fragen/Antworten.

Dateien:
- index.html       App
- data.js          Fragen/Antworten
- manifest.webmanifest  App-Manifest
- sw.js            Offline-Cache
- icon.svg         App-Symbol

Für die Installation auf dem iPad:
1. Alle Dateien gemeinsam auf einen Webserver hochladen.
2. Die URL der index.html in Safari öffnen.
3. Teilen -> Zum Home-Bildschirm.
4. Das neue Symbol startet die App im Vollbild.

Wichtig: manifest/service worker funktionieren nur zuverlässig über HTTPS
(eine normale lokale file://-Datei reicht dafür nicht).
