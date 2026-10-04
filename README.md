# pitambaracharya.com

Personal academic website of Pitambar Acharya — plain HTML + CSS, hosted free on GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | All page content (edit text here) |
| `style.css` | Colors, fonts, layout |
| `CNAME` | Tells GitHub Pages to serve the site at www.pitambaracharya.com |
| `cv.pdf` | Your CV (the "CV" / "Download CV" links point here) — replace it whenever you update your CV |
| `profile.jpg` | **Add yourself (optional)** — square photo; shows "PA" initials if missing |

## Before uploading

Content, email, Google Scholar, ORCID, LinkedIn and publication DOIs are already filled in from the CV.
Optional: add `profile.jpg`, and once you have a GitHub account, un-comment the GitHub link in the Contact section of `index.html`.

## Deploy step by step

1. **Create a GitHub account** at https://github.com (if you don't have one).
2. **Create a repository**: click **New** → name it `pitambaracharya.github.io`
   (replace with *your* username) → **Public** → **Create repository**.
3. **Upload files**: on the repo page click **Add file → Upload files**, drag in
   `index.html`, `style.css`, `CNAME`, `cv.pdf` (and `profile.jpg` if you have one) → **Commit changes**.
4. **Enable GitHub Pages**: **Settings → Pages** → Source: *Deploy from a branch* →
   Branch: `main`, folder `/ (root)` → **Save**.
5. **Site is live** in 1–2 minutes at `https://YOUR-USERNAME.github.io`.

## Connect your domain (www.pitambaracharya.com)

At your domain registrar (GoDaddy, Namecheap, Google/Squarespace Domains, etc.), open DNS settings and add:

| Type | Host / Name | Value |
|---|---|---|
| CNAME | `www` | `YOUR-USERNAME.github.io` |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

Remove any old A/CNAME records that point elsewhere (e.g., a previous site builder).

Then in GitHub **Settings → Pages → Custom domain**, enter `www.pitambaracharya.com`, click **Save**,
and once the DNS check passes (minutes to a few hours), tick **Enforce HTTPS**.

## Updating later

Edit `index.html` directly on GitHub (pencil icon) → **Commit changes**. The site updates within a minute.
