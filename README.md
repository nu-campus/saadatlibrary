# Saadat Library — redirect page

Share this repo's GitHub Pages link. Visitors see a short animated screen and are sent to the live site.

## Setup (once)
1. Edit `site.json` (and the `FALLBACK` constant in `index.html`) with your current website address.
2. Push to GitHub → **Settings → Pages** → deploy from branch `main`, folder `/ (root)`.
3. **Settings → Actions → General → Workflow permissions** → *Read and write permissions*.

## Changing the address later
**Releases → Draft a new release** → set the **title** to the new address (e.g. `https://new-host.com`), tick *Set as latest*, click **Publish**.
The workflow rewrites `site.json`; the live redirect updates in about a minute. No code changes needed.

Preview without redirecting: add `?noredirect` to the page URL.
