# myWebsite

Personal site — plain HTML/CSS/JS, no build step.

## Files
- `index.html` — all content (hero, projects, about, contact)
- `style.css` — styling
- `script.js` — just sets the footer year

## Things to fill in
- Project links (`href="#"` on each "View →") and real project copy in `index.html`
- About section paragraph and facts list
- GitHub / LinkedIn / Resume links in the contact section

## Run locally
```
python3 -m http.server 8000
```
then open http://localhost:8000

## Deploy (free, easy)
Push this folder to a GitHub repo, then enable **GitHub Pages** in the repo
settings (branch: main, folder: /). Or drag the folder into
[Netlify Drop](https://app.netlify.com/drop) for an instant URL.
