# tahirasmith.github.io

Personal website of Tahira Smith, live at **https://tahirasmith.github.io**.

Plain HTML and CSS, hosted free on GitHub Pages. No build step: edit a file, commit to `main`, and the site updates in about a minute.

## Files

| File | What it does |
|---|---|
| `index.html` | The whole site. Search for `EDIT ME` to find the parts to personalize. |
| `style.css` | Colors, fonts, layout. Change the variables at the top to restyle. Dark mode is automatic. |
| `robots.txt`, `sitemap.xml` | Tell Google the site exists and can be indexed. |
| `404.html` | Page shown for broken links. |
| `favicon.svg` | Browser tab icon. |

## Getting it on Google

1. **Make sure Pages is on:** repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)`.
2. Go to [Google Search Console](https://search.google.com/search-console) → **Add property** → **URL prefix** → `https://tahirasmith.github.io/`.
3. Choose **HTML tag** verification. Copy the `content="..."` code, paste it into the commented-out `google-site-verification` line in `index.html`, uncomment it, commit, wait a minute, then click **Verify**.
4. In Search Console → **Sitemaps**, submit `sitemap.xml`.
5. In **URL Inspection**, enter `https://tahirasmith.github.io/` and click **Request indexing**.

Google usually indexes a new site within a few days to a couple of weeks. Linking to the site from your GitHub profile, LinkedIn and résumé speeds this up and helps it rank for your name.

When you add pages or make big changes, update `<lastmod>` in `sitemap.xml`.

## Adding a résumé

Drop `resume.pdf` in the repo root and uncomment the Résumé button in the Contact section.
