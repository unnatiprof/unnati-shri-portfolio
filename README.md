# Unnati Shri — Java Backend Developer Portfolio

A responsive, static portfolio website built with semantic HTML, CSS, and vanilla JavaScript. It has no runtime dependencies and can be hosted on GitHub Pages, Netlify, or Vercel as a static site.

## Contents
- `index.html` — complete website, styling, and interactive navigation
- `public/Unnati-Shri-Resume.pdf` — supplied resume PDF for download
- `public/favicon.svg` — portfolio favicon
- `src/` — reserved for future modular source if the site is migrated to a component framework
- `robots.txt`, `sitemap.xml` — basic crawl files; update sitemap URL after choosing a production domain

## Run locally
Open `index.html` directly in a browser, or serve the folder with any static web server. For example, with Python installed:

```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Deploy to GitHub Pages
1. Create a GitHub repository and upload the contents of this folder.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait for GitHub Pages to publish the site; copy the actual URL shown in Settings → Pages.
5. Replace the placeholder `https://YOUR-DOMAIN.example/` in `sitemap.xml` with the actual production URL. Add a canonical URL to `index.html` once the final domain is known.

Alternatively, import the repository into Netlify or Vercel and deploy it as a static site. No build command is required; the publish directory is the repository root.

## Updating content
- Edit the text and project cards in `index.html`.
- Replace `public/Unnati-Shri-Resume.pdf` when the resume is updated, keeping the same filename so the download link continues to work.
- LinkedIn and GitHub links are taken from the hyperlinks embedded in the supplied resume.
- FinTrack and SkillSync repository links and the Smart Hostel live demo are taken from the supplied resume's embedded links. Verify these destinations before sending the portfolio to recruiters.
- Update Open Graph and canonical metadata when a final public domain is available.

## Quality notes
The page uses responsive CSS, a keyboard-accessible mobile navigation toggle, visible focus states, semantic sections, reduced-motion support, real email/telephone links, and a direct resume download. It does not use a contact form that could falsely imply message delivery. No tracking scripts or external runtime dependencies are included.
