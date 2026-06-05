# Raunak Kapoor — Portfolio Website

Personal portfolio for **Raunak Kapoor**, ServiceNow ITOM Developer with 12+ years of experience designing enterprise-scale ITOM, ITSM, and CMDB solutions. CIS-Discovery Certified. Based in Bangalore, India.

## Live Demo

[https://resume.raunak404.workers.dev/](https://resume.raunak404.workers.dev/)

## Sections

- **Hero** — Introduction, CTA buttons (View Work / Download Resume), and CIS-Discovery badge overlay
- **Stats Bar** — Animated counters: years of experience, companies, certifications, and technologies
- **About Me** — Professional background and expertise cards (ServiceNow Platform, Development & APIs, Cloud & DevOps)
- **Technical Skills** — Skill matrix grouped by: Platform, Scripting & Dev, Integrations, Cloud & DevOps, Database, Frameworks
- **Work Experience** — Timeline of roles across Alcor Solutions, Cognizant, Eurofins IT Solutions, HCL Technologies, and Wipro
- **Certifications & Badges** — Featured CIS-Discovery cert plus grid of HackerRank, ITIL v4/v3, LinkedIn Learning, and ServiceNow badges
- **Tools & Projects** — Open-source utilities: Chrome extension, JSON Formatter, Subnet Calculator, IPv4 Address Formatter, and this portfolio
- **Education** — MBA (IILM) and BCA (IISE), plus internships
- **Contact** — Phone/WhatsApp, email, and LinkedIn; "Hire Me" and "Download Resume" CTAs

## Features

- **Dark / Light theme toggle** — persisted via `localStorage`, respects `prefers-color-scheme`
- **Scroll reveal animations** — Intersection Observer-based fade and slide-in effects
- **Animated stats counters** — numbers count up when the stats bar scrolls into view
- **Active nav highlighting** — navbar and mobile bottom nav track the current section
- **Mobile bottom navigation** — fixed five-tab bar for Home, About, Work, Certs, and Contact
- **Back-to-top button** — appears after 400 px of scroll
- **Frosted glass navbar** — transitions on scroll
- **Responsive layout** — Bootstrap 5 grid, tested across desktop and mobile

## Technologies

- **HTML5 / CSS3 / JavaScript** — no build step; vanilla JS throughout
- **Bootstrap 5.3.3** — responsive grid and utilities
- **Font Awesome 6.5.1** — icon toolkit
- **Google Fonts** — Space Grotesk (headings), Inter (body), Cormorant Garamond (footer)
- **Cloudflare Workers** — hosted via `wrangler.jsonc` on `resume.raunak404.workers.dev`
- **smooth-scroll.js** — custom smooth scrolling

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/raunak1264/raunakweb.git
   ```
2. Open `index.html` directly in a browser — no server or build step required.

## Contact

Raunak Kapoor · [rawnakkapoor@gmail.com](mailto:rawnakkapoor@gmail.com) · [linkedin.com/in/raunakkapoor](https://www.linkedin.com/in/raunakkapoor/)
