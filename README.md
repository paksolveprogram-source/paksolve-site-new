# PakSolve Website

A simple, professional educational website for the PakSolve program.

## Pages

- **Home** (`index.html`) – Main landing page and program overview
- **FAQ** (`faq.html`) – Frequently asked questions
- **Sign Up** (`signup.html`) – Interest signup form

## Hosting on GitHub Pages

1. Create a new repository on GitHub (e.g. `paksolve-website`).
2. Push this folder to the repo (all files in the root, or in a branch).
3. In the repo: **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Select the branch (e.g. `main`) and folder **/ (root)**.
6. Save. Your site will be at `https://<username>.github.io/<repo-name>/`.

If the repo is named `paksolve-website`, use that in the URL. If you use a **project site** (`username.github.io`), put `index.html` at the root and the site will be at `https://username.github.io`.

## Editing the site

- **Content**: Edit the `.html` files (text, links, form fields).
- **Look and feel**: Edit `styles.css`. At the top, the `:root` section has all main colors and fonts—change those to match your brand.

## Signup form

The signup form currently has `action="#"`, so it does not send data anywhere. To collect responses you can:

- Use a form service (e.g. [Formspree](https://formspree.io), [Netlify Forms](https://www.netlify.com/products/forms/)) and set the form `action` to their URL, or
- Add a small server/backend and point the form there.
