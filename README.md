# Ndelo ya Rixaka - Static Website Package

## What is included
- `index.html` - main website file
- `styles.css` - styling with a modern green & white palette
- `script.js` - small JavaScript for form UX
- `assets/logo.jpg` - your uploaded logo
- `README.md` - this file with deployment and setup instructions

## Quick local preview
1. Unzip the package and open `index.html` in your browser.

## Configuring the contact form (Formspree)
1. Go to https://formspree.io and sign up.
2. Create a new form and copy the form endpoint ID (it looks like `https://formspree.io/f/xyzabc`).
3. In `index.html`, replace `https://formspree.io/f/{your-form-id}` with your actual Formspree endpoint URL.
4. Formspree will forward submissions to the email you verify during setup (use ndeloyarixaka@gmail.com).

## PayFast donation button
- The Donate button is a placeholder. Once you have a PayFast donation link, replace the `href="#"` on the Donate button in `index.html` with your PayFast URL.

## Deploying to GitHub Pages
1. Create a new GitHub repository (e.g. `ndelo-website`) and push the contents of this package.
2. In the repository settings, under "Pages", select the branch `main` (or `master`) and `/ (root)` as the folder.
3. Save — GitHub will provide a site URL in a few minutes: `https://<your-username>.github.io/<repo-name>/`

## Optional: Use a custom domain
- You can add a `CNAME` file with your custom domain and configure DNS to point to GitHub Pages. Follow GitHub's documentation for custom domains.

## Need help?
If you'd like, I can:
- Create the GitHub repo and push the site (I will provide instructions for you to add me or you can provide a personal access token), OR
- Walk you step-by-step (with screenshots) to deploy the site yourself.
