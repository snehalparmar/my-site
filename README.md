# Snehal Personal Website

A static personal website inspired by a clean, sustainability-style layout.

## Files

- `index.html` — page structure and content from resume + Stack Overflow profile
- `styles.css` — minimalist responsive styling
- `resume.pdf` — downloadable PDF resume linked from hero section
- `resume.txt` — extracted text from provided resume PDF
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment workflow

## Run locally

Open `index.html` directly in a browser, or run a local server:

```bash
cd /Users/test/dev/my-site
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository with the default branch set to `main`.
2. In GitHub, go to **Settings → Pages** and set **Source** to **GitHub Actions**.
3. Push to `main` (or run the workflow manually from **Actions**).
4. Your site will be published at:
   - `https://<username>.github.io/<repository>/`
   - or `https://<username>.github.io/` if the repository is named `<username>.github.io`

## Data sources

- Resume PDF provided by user
- Stack Overflow profile: `https://stackoverflow.com/users/1965509/snehal-parmar`
