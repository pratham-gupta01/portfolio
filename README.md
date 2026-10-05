# Pratham Gupta — Freelance iOS Portfolio

A static, single-page freelance portfolio focused on iOS bug fixing, API/Firebase/SDK integration, and small feature development.

## Why this stack?

This version uses plain HTML, CSS, and JavaScript.

- No build step
- No npm dependencies
- Works directly on GitHub Pages
- Fast and easy to edit
- Easy to move to another static host later

## Files

```text
ios-freelance-portfolio/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## 1. Replace placeholders

Open `index.html` and replace:

- `EMAIL_HERE`
- `LINKEDIN_URL_HERE`
- `GITHUB_URL_HERE`
- `WHATSAPP_NUMBER_HERE`
- `WEBSITE_URL_HERE`

For WhatsApp, use the international phone number without `+`, spaces, or dashes.

Example:

```text
919876543210
```

Do not leave placeholder contact details on the public site.

## 2. Test locally

You can simply double-click `index.html`.

For a more realistic local server, from this folder run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 3. Create the Git repository

Inside the project folder:

```bash
git init
git add .
git commit -m "Create freelance iOS portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY`.

## 4. Enable GitHub Pages

On GitHub:

1. Open the repository.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main**.
6. Select folder **/(root)**.
7. Save.

After GitHub finishes publishing, it will show the public Pages URL.

## 5. Content editing

Most content is intentionally in `index.html`.

### Change your headline

Search for:

```html
<h1>Fix. Improve.<br /><span>Ship.</span></h1>
```

### Change services

Search for:

```html
<section id="services"
```

Each `.service-card` represents one service.

### Change case studies

Search for:

```html
<section id="work"
```

Keep the case studies anonymized unless you have permission to disclose project/client information.

### Change technologies

Search for:

```html
<section id="tech"
```

### Change pricing

Search for:

```html
<section class="pricing"
```

### Change visual styling

Most colors, spacing, typography, and sizes are controlled through variables at the top of `styles.css`.

## Important positioning rule

The site is intentionally positioned as a freelance iOS specialist, not as a generic full-stack developer or job-seeking resume.

Keep the primary message focused on:

- iOS bug fixing
- API / Firebase / SDK integration
- Small iOS feature development

Flutter should remain a secondary service.

## Contact form

No backend contact form is included. Direct email, LinkedIn, GitHub, and WhatsApp links are used because they work with a static GitHub Pages deployment.

If a form is needed later, use a third-party form endpoint/service rather than adding a custom backend to GitHub Pages.
