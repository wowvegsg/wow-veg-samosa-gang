# Wow Veg Samosa Gang — Website v1.0

Static responsive website for Wow Veg Samosa Gang, designed for GitHub Pages.

## Files
- `index.html` — homepage, menu highlights, catering, location and contact details
- `style.css` — responsive saffron, green and cream design
- `script.js` — mobile navigation and current year
- `404.html` — not-found page
- `robots.txt`, `sitemap.xml` — basic search engine files
- `images/logo.png` — add the business's approved logo here

## Before launch
1. Confirm the exact street number. Public listings currently show both 42 and 43 High Street; this template uses 42 High Street pending confirmation.
2. Verify menu prices and food descriptions with the business.
3. Replace `images/logo.png` with the approved logo. If it is not present, the text logo fallback appears.
4. Check all image licensing and replace images with the business's own food photography where possible.
5. Confirm current opening hours and the preferred online ordering URL.
6. The catering CTA uses a WhatsApp chat link to the supplied business phone number. Confirm WhatsApp is enabled for that number.

## Local preview
Open this folder in VS Code and open `index.html` in a browser. For a smoother workflow, use the VS Code Live Server extension.

## GitHub Pages deployment
Create a public repository named `wow-veg-samosa-gang`, upload the contents of this folder (not the parent folder), then open Settings → Pages. Select "Deploy from a branch", choose `main` and `/(root)`, and save.

When ready to attach the custom domain, enter `wowvegsg.com` under Settings → Pages → Custom domain. Configure GoDaddy DNS according to GitHub Pages' current instructions. A typical apex configuration uses A records for GitHub Pages' published IPs and `www` CNAME pointing to `<your-github-username>.github.io`; verify the current values in GitHub's official docs before changing existing records. Preserve any email-related MX/TXT records.
