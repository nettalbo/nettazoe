# Netta Zoe · portfolio

Static site: plain HTML, CSS and a little inline JavaScript. No build step, no dependencies.

## Pages
- `index.html` home, `about.html` about
- Case studies: `leumi-ai.html`, `transfer.html`, `ashdod.html`, `vouchers.html`, `book.html`, `sundance.html`
- `404.html` page-not-found (most hosts pick it up automatically)
- `robots.txt`, `sitemap.xml` for search engines

## Assets
- `assets/` images, videos, `resume.pdf` (+ `resume.jpg` preview), favicons, `og.jpg` (link preview image)
- `assets/fonts/` Geist and Geist Mono (SIL Open Font License, free for web use)

## Domain
All canonical and link-preview URLs point to `https://www.nettazoe.com`. If the domain changes, search and replace it in the HTML files, `robots.txt` and `sitemap.xml`.

## Publish
- Netlify: drag this folder onto app.netlify.com/drop, then Domain settings → add `nettazoe.com`
- Vercel: push the folder to a GitHub repo → vercel.com → Add New Project → Deploy → Settings → Domains → `nettazoe.com`
- At your domain registrar, point the DNS records to the host as the host's domain screen instructs.
