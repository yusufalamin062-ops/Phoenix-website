[README.md](https://github.com/user-attachments/files/34774703/README.md)
# Phoenix – Tech Company Website

A responsive, single-page website for **Phoenix**, a fictional technology company. Built as a school project using plain HTML, CSS and JavaScript, with no frameworks or build tools.

**Live site:** https://stunning-malasada-48557d.netlify.app*

## Pages and sections

| Section | What it contains |
| --- | --- |
| **Home** | Hero with an animated ember background, headline, call-to-action buttons and animated stats |
| **Services** | Six service cards: cloud engineering, AI and automation, web and mobile apps, cybersecurity, data platforms, support and maintenance |
| **Contact** | Company contact details and a message form with validation |

## Features

- Fully responsive layout for phones, tablets and desktops
- Mobile navigation menu that slides open
- Smooth scrolling and a navigation bar that highlights the current section
- Animations: headline reveal, rising ember particles (HTML canvas), scroll-triggered fade-ins, count-up numbers, card hover effects, floating form labels
- Automatic light and dark mode based on the visitor's device settings
- Accessibility: keyboard focus styles, ARIA labels, and animations switch off for visitors who prefer reduced motion

## Technologies

- HTML5
- CSS3 (custom properties, grid, flexbox, keyframe animations)
- Vanilla JavaScript (Intersection Observer, Canvas API)
- Google Fonts: Bricolage Grotesque and DM Sans

## Project structure

```
phoenix-website/
├── index.html    # the entire site: markup, styles and scripts
└── README.md
```

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No installation is needed.

```bash
git clone https://github.com/your-username/phoenix-website.git
cd phoenix-website
```

## Deploy

**Netlify**
1. Sign in at [netlify.com](https://www.netlify.com) with GitHub.
2. Choose **Add new site**, then **Import an existing project**, and select this repository.
3. Leave the build command empty and click **Deploy**.

**GitHub Pages**
1. Go to **Settings**, then **Pages**.
2. Set the branch to `main` and the folder to `/ (root)`, then save.

## Customize

- **Colors:** edit the variables at the top of the `<style>` block (`--ember`, `--gold`, `--ink` and others).
- **Text and contact details:** edit the content directly in `index.html`. The email, phone number and address are placeholders.
- **Contact form:** the form currently shows a confirmation message only and does not send data. To collect real messages, use [Netlify Forms](https://docs.netlify.com/forms/setup/) or a service such as Formspree.

## Notes

Phoenix is a fictional company created for educational purposes. All names, contact details and statistics are placeholders.

## Author

Yusuf Al-amin – ABUAD / Software Engineering
– 2026
