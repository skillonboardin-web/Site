<div align="center">
✍️ Skill on Board
Skill courses and art workshops for schools and corporate events
Handwriting · Calligraphy · Art · Craft · Phonics · Spoken English
Online and offline, across India.
🌐 Visit the site · 📸 Instagram · ⭐ Leave a review
</div>
---
✨ About
This is the official website for Skill on Board. It is a fast, single-page site that helps schools and companies discover our courses and workshops and request a demo session.
🧩 What's on the page
Section	What it does
Hero	Introduces Skill on Board with calls to action
Courses	Skill-based courses for students
Workshops	School and corporate event workshops
About	Who we are and how we teach
Inside our sessions	Photo gallery of student and participant work
Google reviews	Live reviews widget, plus "Read all reviews" and "Write a review" buttons
Request a demo	Enquiry form that prepares a message to send by WhatsApp, email or Instagram
Also included: light and dark mode, a mobile-first responsive layout, and accessible focus styles.
🗂️ Project structure
```
.
├── Index.html     # the whole site: HTML, CSS and JS in one file
├── sitemap.xml    # sitemap for search engines
├── robots.txt     # crawl rules, points to the sitemap
├── favicon.ico, favicon-*.png, apple-touch-icon.png   # tab and home-screen icons
└── README.md      # you are here
```
There is no build step and no dependencies to install. Open `Index.html` in a browser to preview it.
🛠️ Editing the site
Most day-to-day updates are in the `<script>` block near the bottom of `Index.html`:
```js
var CONTACT = { whatsapp: "918122488997", email: "Skillonboard.in@gmail.com" };
var PHOTOS = [ /* { src, alt, cap } gallery images */ ];
var TESTIMONIALS = []; // e.g. [{ quote: "...", who: "Principal, School name" }]
```
Gallery: add or replace items in `PHOTOS`. Each item takes `src`, an optional `alt` and an optional `cap` (caption).
School quotes: fill `TESTIMONIALS` and a "What schools say" section appears automatically. It stays hidden while the list is empty.
Contact details: change `CONTACT` and the enquiry form updates its WhatsApp and email buttons.
Google reviews: the section uses a SociableKit widget. Its embed code lives in the `#reviews` section.
🔍 SEO
Page title, meta description and canonical URL are set in the `<head>`.
`sitemap.xml` lists the site, and `robots.txt` points crawlers to it.
After deploying, submit `https://innovativeskillonboard.site/sitemap.xml` in Google Search Console.
When you update the page, refresh the `<lastmod>` date in `sitemap.xml`.
🚀 Deploying
It's a static site, so any static host works. Upload `Index.html`, `sitemap.xml` and `robots.txt` to the web root. Some hosts expect the main file to be named `index.html` in lowercase, so rename it if needed.
📬 Contact
📞 Call or WhatsApp: 81224 88997
✉️ Email: Skillonboard.in@gmail.com
📸 Instagram: @skillonboard
---
<div align="center">
Made with ❤️ for curious young learners.
</div>
