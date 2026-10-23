# Shamsheer Hussain — Portfolio

Personal portfolio website of **Shamsheer Hussain Syed**, a Product Manager with 5+ years in fintech, now applying AI to build better financial products.

**Live site:** [shamsheerportfolio.netlify.app](https://shamsheerportfolio.netlify.app)

**Connect:** [LinkedIn](https://www.linkedin.com/in/shamsheerhussainsyed/) · [GitHub](https://github.com/shamsheer-tech18)

## What's on the site

- **Hero:** introduction and photo, sized to fit one screen on desktop
- **About:** career story and key numbers
- **Skills:** grouped skills with a search box
- **Experience:** ICICI Bank, Nordea and TCS, each with the problem, approach and impact
- **How I think:** answers to common product questions
- **Projects:** PM Copilot and ChowPal
- **Beyond the resume:** leadership and personal story
- **Contact:** email with a copy button, plus LinkedIn, GitHub and resume links

## What's in this repository

```
index.html                         the whole website (HTML, CSS and JavaScript in one file)
shamsheer.jpg                      profile photo
Shamsheer_Hussain_Syed_Resume.pdf  resume linked from the Contact section
logos/                             company and university logos (PNG, transparent background)
README.md                          this file
```

The site is plain HTML, CSS and JavaScript. There is no build step and nothing to install.

## Make a change

1. Open `index.html`. On GitHub, click the file, then the pencil icon.
2. Find the text you want to change. Each section starts with a marker such as `id="about"`, `id="skills"`, `id="experience"`, `id="thinking"`, `id="projects"`, `id="beyond"` or `id="contact"`.
3. Edit the text, then click **Commit changes**.
4. Netlify publishes the update automatically, usually within a minute.

To change colors, open the `<style>` block at the top of `index.html`. The color and font choices are listed first, under `:root`.

To replace the photo or the resume, upload a new file with the **same name**. Use the **Add file → Upload files** button on the repository page.

## Deploy with Netlify

This repository is connected to Netlify, so every commit to the `main` branch updates the live site.

First-time setup:

1. In Netlify, choose **Add new site → Import an existing project → GitHub**, then select this repository.
2. Leave the **build command** empty and the **publish directory** blank. The site needs no build.
3. Click **Deploy**.
4. Under **Site configuration → Change site name**, choose a friendly address.

If a change breaks the site, open the **Deploys** tab in Netlify, pick an earlier deploy and choose **Publish deploy** to roll back.

## Preview on your computer (optional)

From inside this folder, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Built with

- Plain HTML, CSS and JavaScript
- Fonts from Google Fonts: Fraunces (headings) and Hanken Grotesk (text)
- Supports light and dark mode, and works on phones, tablets and desktops

## Notes

- Company and university logos belong to their respective owners and are shown to identify where I worked and studied.
- All site content and the photo are © Shamsheer Hussain Syed. Please don't reuse them without permission.
