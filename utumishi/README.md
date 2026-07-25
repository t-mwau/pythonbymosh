# Utumishi Archive Website

Recommended setup details for the responsive journal, book, and materials archive webpage:

- **Website name:** Utumishi Archive
- **Required GitHub repository:** https://github.com/t-mwau/DecodeLabs-Internship
- **Repository folder after cloning:** DecodeLabs-Internship
- **Project folder inside the repo:** utumishi
- **Main HTML file:** utumishi/index.html
- **CSS folder:** utumishi/css
- **Stylesheet file:** utumishi/css/styles.css

## Terminal commands to create the project in the required repository

Run these commands from the directory where you keep your GitHub projects:

```bash
git clone https://github.com/t-mwau/DecodeLabs-Internship.git
cd DecodeLabs-Internship
mkdir -p utumishi/css
touch utumishi/index.html utumishi/css/styles.css
```

After adding your webpage code, save the files and commit them:

```bash
git add utumishi/index.html utumishi/css/styles.css utumishi/README.md
git commit -m "Create Utumishi archive website"
git push origin main
```

## How to open the webpage locally

From inside the `DecodeLabs-Internship` repository folder, run:

```bash
python3 -m http.server 8000 --directory utumishi
```

Then open this address in your browser:

```text
http://localhost:8000
```
