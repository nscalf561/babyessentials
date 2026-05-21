# Daily Baby — GitHub Pages (legal & support)

Static pages for App Store and Google Play URLs.

## Enable GitHub Pages

1. Push this `docs/` folder to GitHub.
2. Repo **Settings → Pages**.
3. **Build and deployment → Source:** Deploy from a branch.
4. **Branch:** `main` (or your default branch), **Folder:** `/docs`.
5. Save. After a minute or two, the site is live at  
   `https://<github-username>.github.io/<repo-name>/`.

## URLs for store listings

| Page | Path |
|------|------|
| Privacy Policy | `/privacy.html` |
| Support | `/support.html` |
| Home | `/` or `/index.html` |

Example (replace with your username and repo):

- `https://yourusername.github.io/daily_baby_photo/privacy.html`
- `https://yourusername.github.io/daily_baby_photo/support.html`

## Custom domain (`www.babyessentials.com`)

`docs/CNAME` is set to `www.babyessentials.com`. In the repo:

1. **Settings → Pages → Custom domain:** enter `www.babyessentials.com`.
2. In **Cloudflare DNS** (or Squarespace if DNS stays there):
   - `www` → **CNAME** → `<github-username>.github.io`
   - Optional: redirect apex `babyessentials.com` → `https://www.babyessentials.com`
3. Wait for DNS + GitHub’s HTTPS certificate (can take up to 24 hours).

Then use:

- `https://www.babyessentials.com/privacy.html`
- `https://www.babyessentials.com/support.html`

## Edit contact / legal name

Update `support@babyessentials.com` and "Baby Essentials" in `privacy.html`, `support.html`, and `index.html` if needed.
