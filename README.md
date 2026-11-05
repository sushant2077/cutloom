# Cutloom public website — GitHub Pages (for @sushant2077)

This ZIP is **only the public informational website**, not the Python video processing backend. Do not place `.env`, `local_data`, `.venv`, model files, social access tokens, project files, source videos, or finished clips in the public repository.

## Your proposed free public URLs

- Website: `https://sushant2077.github.io/cutloom/`
- Terms: `https://sushant2077.github.io/cutloom/terms.html`
- Privacy: `https://sushant2077.github.io/cutloom/privacy.html`

These URLs will work **after** you create the public GitHub repository named `cutloom`, upload these files to its root and enable GitHub Pages. The site is not live merely because this ZIP exists.

## Publish without using CMD

1. Open https://github.com/new. Under your account **sushant2077**, create a repository named exactly **cutloom**, set visibility **Public**. Create it with or without a README.
2. On the repository's Code page select **Add file → Upload files**. Unzip this download and upload the **contents** of `cutloom_public_website` to the repository root: `index.html`, `terms.html`, `privacy.html`, `styles.css`, `assets/` and `.nojekyll` (hidden files may require extra care). Do **not** upload a folder nested inside another `cutloom_public_website` folder.
3. Commit the files. Open **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. Open the website URL above. Make sure all three pages load and that the URL is HTTPS.
5. In TikTok Developer Portal, enter the three exact URLs. Choose **Desktop** platform for Cutloom's local OAuth flow.
6. Select **URL properties → Verify properties → URL prefix**. Try `https://sushant2077.github.io/cutloom/`. Download TikTok's unique signature file and upload it **unchanged** to the GitHub Pages site root, so that it is reachable at `https://sushant2077.github.io/cutloom/<signature-filename>` with an HTTP 200 status. Re-run verification. Do not invent or rename TikTok's file.

Important: TikTok must accept the URL-prefix ownership verification and app review; a shared `github.io` domain is not guaranteed to pass every TikTok restriction. If rejected, use a domain you control or another hosting option that supports TikTok's required verification. Do not claim a successful verification until TikTok shows it.

## Privacy/legal checks before submitting to TikTok

The Terms and Privacy pages reflect the local-first Cutloom workflow based on the currently supplied project. Please review and adjust them to accurately describe the precise version of Cutloom and your own operational practices. For serious production use, have legal wording reviewed for your jurisdiction. The public support link assumes this `cutloom` repository exists; you can replace it with a genuine support email if preferred. These pages must be genuine, not placeholders.

## Site structure

- `index.html` product homepage
- `privacy.html` privacy policy
- `terms.html` terms of service
- `styles.css` responsive design
- `assets/logo.svg` original Cutloom-inspired brand icon
- `assets/studio-preview.webp` cropped screenshot of the existing desktop application
- `.nojekyll` prevents Jekyll processing of the static site

There are no cookies, analytics or remote fonts bundled in the site. GitHub Pages may still collect technical access logs under GitHub's privacy policy.
