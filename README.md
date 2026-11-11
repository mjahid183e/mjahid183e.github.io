# Jahidul Islam — Business Analytics Portfolio

A responsive static portfolio website built with semantic HTML, CSS and vanilla JavaScript. It is designed for GitHub Pages and requires no build step, server, package manager or paid service.

**Repository:** `https://github.com/mjahid183e/mjahid183e.github.io`  
**Expected website:** `https://mjahid183e.github.io/`

## Run locally

1. Open this folder in Visual Studio Code.
2. In the Explorer, right-click `index.html` and choose **Open with Live Server** (after installing the Live Server extension), or double-click `index.html` to preview the basic static page in your browser.
3. Test the top navigation, project listing, case studies, mobile menu and project filters.

## Publish on GitHub Pages

1. Commit the site files on the `main` branch and push them to GitHub.
2. On GitHub, open this repository and select **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then click **Save**.
5. Wait for the Pages deployment workflow to finish. The site should be published at `https://mjahid183e.github.io/`.

GitHub's current instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Before publishing — final review

- [x] Name, universities, degrees and graduation dates added to the homepage.
- [x] GitHub, Gmail compose and LinkedIn links added; Gmail opens with recipient filled and subject left blank.
- [x] Resume linked in the hero and contact panel at `assets/files/Md-Jahidul-Islam-Resume.pdf`. The owner has approved public sharing of the phone number in this PDF.
- [x] The Education section contains *only* postgraduate and undergraduate degrees; mT5 appears under Projects instead.
- [ ] Review project methods and metrics, and add only verified information.
- [ ] Finish the Excel/CSV data-quality demonstration before marking it complete.
- [ ] Replace illustrative graphics with authentic project screenshots if useful.
- [ ] Test the desktop and mobile navigation and project filters before deployment.

## Project structure

```text
.
├── index.html
├── 404.html
├── favicon.svg
├── README.md
├── projects/
│   ├── index.html
│   ├── bangla-text-summarization.html
│   └── excel-csv-data-cleaning.html
└── assets/
    ├── css/style.css
    ├── js/main.js
    ├── images/       # Add real project/profile images here
    └── files/        # Includes Md-Jahidul-Islam-Resume.pdf
```

## Update the website

Edit the relevant file in VS Code, save it, review the local preview, then use GitHub Desktop to review changes, enter a descriptive commit summary (for example, `Update project case study`), click **Commit to main**, and click **Push origin**. GitHub Pages redeploys after changes are pushed to the publishing source.

## Privacy and accuracy

GitHub Pages websites are public. Never upload credentials, tokens, private data or confidential customer/student information. Use a dataset you have permission to share, or use a clearly labelled synthetic/public dataset. Report only results that you actually measured and can reproduce.

## Verified personalization (October 2026)

- Display name: Md. Jahidul Islam
- MSc Business Analytics: King Fahd University of Petroleum and Minerals, Saudi Arabia; expected graduation 2028
- BSc in Computer Science and Engineering: North South University, Bangladesh; graduated 2023
- Contact: mjahid183.e@gmail.com
- LinkedIn: https://www.linkedin.com/in/mjahidulislam01

Project case studies still require real dataset, code and evaluation details before claims of completion.


## Resume and contact

The public resume is `assets/files/Md-Jahidul-Islam-Resume.pdf`. The homepage includes a Download resume link, and the contact panel includes a PDF viewer link. The **Email me** link opens Gmail in a new browser tab with the recipient prefilled and the subject and body blank. It requires the visitor to be signed into Gmail; people without Gmail can use the address `mjahid183.e@gmail.com` manually. The resume is approved for public sharing by the site owner, including its contact number.

## Personal portrait

The About section displays `assets/images/profile.webp` (your provided portrait).
To replace it later, export a new image to that exact path and keep the file name, or update the `src` attribute in `index.html`. The portrait is lazy-loaded and does not replace the JI header mark.
