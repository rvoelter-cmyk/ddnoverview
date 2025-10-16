# DDN Executive Overview — Static Website

Diese Repository-Vorlage enthält eine moderne, responsive One-Page-Website basierend auf dem hochgeladenen `Executive Overview DDN.pdf`.

## Inhalt
- `index.html` — Hauptseite (Deutsch)
- `styles.css` — Styling
- `script.js` — Kleines JS für Smooth-Scrolling
- `README.md` — Diese Datei

## Wie du die Seite auf GitHub Pages hostest

1. Erstelle ein neues Repository auf GitHub (zum Beispiel `ddn-overview`) oder nutze ein existierendes.
2. Entpacke dieses ZIP und committe die Dateien:
```bash
git init
git add .
git commit -m "Initial DDN overview site"
git branch -M main
git remote add origin https://github.com/<DEIN_GITHUB_USERNAME>/ddn-overview.git
git push -u origin main
```
3. Gehe zu den Repository-Einstellungen → Pages → Branch: `main` / `/ (root)` → Save.
4. Nach kurzer Zeit ist die Seite verfügbar unter: `https://<DEIN_GITHUB_USERNAME>.github.io/ddn-overview`

Wenn du möchtest, kann ich dir die `git`-Befehle anpassen, falls du ein anderes Repo-Naming oder Organisationen verwendest.

## Hinweise
- Texte stammen aus dem bereitgestellten PDF (Executive Overview).
- Ersetze bei Bedarf Logos, Bilder und zusätzliche Grafiken im Ordner `assets/`.
