# DANGId Home Care Website

A responsive website for **DANGId Home Care**, an international non-medical home care company that supports older adults with companion care, personal care and home support.

**Live site:** https://dangidhomecare.com

![DANGId Home Care homepage](screenshot.png)

## Features

- Four pages in one site: **Home, Services, Booking and Contacts**
- Fully **mobile responsive**, with a collapsing menu on phones
- Automatic **dark mode** for visitors whose device uses it
- Hero section, "Find care near you" search strip, service tiles, About section, "How to get started" steps, FAQ and testimonial sections
- **Video section** with a built-in player (no YouTube embed)
- **Booking request form** with a confirmation message
- Accessible basics: keyboard focus styles, labelled form fields, image alt text
- **SEO basics:** page title, meta description, Open Graph tags, structured data (JSON-LD), `sitemap.xml` and `robots.txt`

## Built with

- HTML5
- CSS3 (custom properties, grid and flexbox)
- Vanilla JavaScript (no frameworks or libraries)
- Google Fonts (Poppins and Nunito Sans)
- Built with AI assistance (Claude) and deployed on Hostinger

## Project structure

```
index.html      The whole site (all four pages)
sitemap.xml     Sitemap for search engines
robots.txt      Crawler rules
images/         Photos used on the site
video/          Introduction video
```

## Run it locally

1. Download or clone this repository.
2. Open the folder in VS Code and install the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.

You can also open `index.html` directly in a browser.

## Deploy

Upload `index.html`, `sitemap.xml`, `robots.txt` and the `images` and `video` folders to the `public_html` folder of any web host (this project uses Hostinger).

## Notes

- The booking form is front-end only. It shows a confirmation message but does not send an email yet. Connect it to a form service or backend to receive requests.
- The testimonials are sample text.
- Use only photos and video you have the right to share publicly. Replace the files in `images/` and `video/` with your own if needed.

## Author

**Meera (Data with Meera)**
GitHub: https://github.com/miracle003-hub
LinkedIn: https://www.linkedin.com/in/miracle-ikechukwu-data

