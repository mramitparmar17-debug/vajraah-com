# Vajraah Digital website — GitHub Pages

A responsive static website for Vajraah Digital. Built with plain HTML, CSS and JavaScript. No build step required.


## Publish with GitHub Pages
1. Sign in to GitHub and create a repository named `vajraah-com` (public recommended for GitHub Pages on the free plan).
2. Upload all files and folders from this package into the repository root. `index.html` must be at the root.
3. Open **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, and Save.
6. Wait for GitHub Pages to publish. The temporary URL will look like `https://YOUR-USERNAME.github.io/vajraah-com/`.

## Connect vajraah.com
1. In repository **Settings → Pages → Custom domain**, enter `vajraah.com` and Save. GitHub will add/update the `CNAME` file in the repository.
2. At your domain DNS manager (Hostinger if DNS is managed there), add these DNS records for the apex domain:
   - A — Host/Name: `@` — Value: `185.199.108.153`
   - A — Host/Name: `@` — Value: `185.199.109.153`
   - A — Host/Name: `@` — Value: `185.199.110.153`
   - A — Host/Name: `@` — Value: `185.199.111.153`
3. Add a `www` CNAME record:
   - CNAME — Host/Name: `www` — Value: `YOUR-USERNAME.github.io` (replace with your actual GitHub username; do not include the repository name for a user/org site domain routing when custom domain is configured as documented).
4. Remove conflicting A, AAAA, CNAME, or parking records for `@` and `www` if present. Do not delete MX/email records.
5. Back in GitHub **Settings → Pages**, wait for DNS check to pass, then enable **Enforce HTTPS** when the option appears.
6. Test both `https://vajraah.com` and `https://www.vajraah.com`.

## Keep vajraah.in
For SEO and clarity, use `vajraah.com` as your primary website. Later, configure `vajraah.in` to permanently (301) redirect to the matching `.com` page. Avoid publishing two identical sites on both domains.

## Before launch: personalize
- Confirm the WhatsApp number and email in `index.html`.
- Replace placeholder social profile URLs in the footer with Vajraah's actual profiles.
- Add actual case studies, client logos and verified results before making performance claims.
- Check canonical URL and meta description in `index.html`.
- Add GA4 and Google Search Console after publishing.

