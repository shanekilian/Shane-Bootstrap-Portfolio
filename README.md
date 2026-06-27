# Portfolio | Shane Kilian

A personal portfolio website built with **HTML5, CSS3, and Bootstrap 5**, showcasing my projects, background, and contact details. Built as part of the Zaio Full Stack Bootcamp.

🔗 **Live site:** https://shane-bootstrap-portfolio.netlify.app/


## Sections Implemented

- **Home** — Hero banner with name and tagline, full-screen background image
- **About Me** — Profile photo, personal details (name, profile, email, phone), skills badges (HTML, CSS, git)
- **Projects** — Showcase of 6 completed projects (Tesla, Netflix, YouTube, and 3 ATC-related systems), each with a description and tech stack used
- **Print Résumé** — Instruction prompt directing visitors to use their browser's print function (`Ctrl+P` / `Cmd+P`) to generate a clean résumé view
- **Contact** — Social links (Instagram, LinkedIn, GitHub) and a contact form (HTML structure only — no backend submission handler connected)


## Bonus Features

- **Print-ready résumé view** — A dedicated `@media print` stylesheet (see `style.css`) automatically reformats the page into a clean, condensed, one-page, black-and-white résumé layout when printed or saved as PDF. This includes:
  - Hiding navigation, hero banner, footer, contact form, and social icons during print
  - Removing project screenshots and links to save space
  - Compact spacing, smaller fonts, and flattened card borders optimized for paper
  - No JavaScript used — achieved entirely through native browser print behavior + Bootstrap's `.d-print-none` utility class + custom CSS
- **Custom font pairing** — Courier Prime (monospace, typewriter-style) for body text paired with Inter for headings and navigation, chosen deliberately for visual contrast between serif/monospace and clean sans-serif
- **No-JavaScript constraint** — The entire site (including print functionality) runs on pure HTML and CSS only, with no Bootstrap JS bundle or custom scripts


## Built With

- [Bootstrap 5.0.2](https://getbootstrap.com/) — layout, grid, and utility classes
- [Bootstrap Icons](https://icons.getbootstrap.com/) — social and UI icons
- [Google Fonts](https://fonts.google.com/) — Courier Prime, Inter
- Basic HTML5 & CSS3 — no JavaScript



## Notes

- Scrollspy (auto-highlighting the active nav link while scrolling) was intentionally **not implemented**, as it requires Bootstrap's JavaScript bundle, which falls outside this project's no-JavaScript constraint.
- The contact form is for visual/structural demonstration only; it is not connected to a backend or email service.

---

Developed by Shane Kilian using Bootstrap, for the Zaio Bootstrap course.
