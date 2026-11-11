# Winston Raj H — Data Science Portfolio

A responsive React + Vite portfolio with a black/neon-red visual direction inspired by the supplied reference video. Includes hero, about, skills, career timeline, six project cards with detail modals, education, contact form and resume download.

## Run locally
1. Install Node.js 18+ (or current LTS).
2. Extract this project and open its folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL printed by Vite.
5. Run `npm run build` to create the production build in `dist/`.

## Resume
The final resume is in `public/resume.pdf`; the hero and footer download links use this file. Replace it with a newer PDF using the same filename to update the download.

## Add your real links
- In `src/App.jsx`, replace the LinkedIn/GitHub placeholder with your actual profile URLs when available.
- Add repository and live-demo URLs to `src/data/projects.js` only after verifying them. They are intentionally omitted rather than fabricated.
- The contact form currently opens the visitor's default email application using `mailto:`. For direct website submissions, connect a backend or a form service and replace the `submit` handler in `src/App.jsx`.

## Project evidence
Project cards and detail views use the descriptions and technologies supplied by Winston. Dataset specifics, screenshots, measured results, model scores, repository links and live demos were not supplied, so the site does not claim them. Abstract CSS artwork is used instead of pretending it is a real project screenshot. The supplied 49-second video is treated as a visual design reference, not a project walkthrough.

## GitHub
Create a new GitHub repository, then from this folder run:
```bash
git init
git add .
git commit -m "Add Winston Raj H data science portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## Deploy on Vercel
1. Sign in to Vercel and import the GitHub repository.
2. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
3. Deploy. Vercel will provide a public URL.
4. To use a custom domain, add it under the Vercel project's Settings → Domains and follow the DNS instructions from your domain provider.

## Before publishing
Verify dates, role titles, project descriptions and contact details. Add real LinkedIn/GitHub links, repository/demo URLs and any verified project screenshots/results.
