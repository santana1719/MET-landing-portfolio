**[LIVE DEMO — View the Website](https://santana1719.github.io/MET-landing-portfolio/)**

# The MET — Landing Page

A responsive landing page for The Metropolitan Museum of Art, built using HTML5 and SCSS based on a Figma design.

## About the Project

The MET Landing Page is a single-page educational frontend project inspired by The Metropolitan Museum of Art in New York City.

The website presents museum opening hours, exhibition highlights, online exploration opportunities, and contact information.

The main goal of this project was to practice responsive web development, semantic HTML, modular SCSS architecture, and CSS-based interactions.

## Features

- **Responsive Design** — layouts adapted for mobile, tablet, and desktop screens.
- **Full-Screen Navigation** — animated slide-in menu implemented with CSS `:target`.
- **Scroll Locking** — prevents background scrolling while the navigation menu is open using CSS `:has()`.
- **Smooth Scrolling** — smooth navigation between page sections.
- **Museum Hours** — opening hours for The Met Fifth Avenue and The Met Cloisters.
- **Exhibition Gallery** — images, descriptions, and dates of featured exhibitions, with a link to the official museum website.
- **Explore Online** — informational cards about museum collections, travel, and virtual tours.
- **Contact Information** — clickable phone numbers and Google Maps links.
- **Contact Form** — built-in HTML validation and automatic form reset. The form does not send data to a server.
- **Sticky Footer** — a responsive background image revealed beneath the main page content.
- **Interactive Styles** — CSS transitions, hover effects, and keyboard focus states.

## Technologies Used

- **HTML5** — semantic markup and page structure.
- **CSS3** — responsive layouts, transitions, and interactive states.
- **SCSS (Sass)** — variables, nesting, reusable mixins, and modular stylesheets.
- **BEM Naming Convention** — consistent naming of CSS classes.
- **Parcel** — development server and production builds.
- **ESLint, Stylelint, and Linthtml** — code quality tools.
- **Git & GitHub** — version control and repository hosting.
- **GitHub Pages** — website deployment.

## Responsive Design

The project uses reusable SCSS media query mixins for different screen sizes:

- **Mobile:** below 744px.
- **Tablet:** 744px–1259px.
- **Desktop:** 1260px and above.

## Project Structure

```text
src/
├── images/               # Images and icons
├── scripts/
│   └── main.js           # JavaScript entry point
├── styles/
│   ├── blocks/           # Styles for page sections
│   ├── _variables.scss   # SCSS variables
│   ├── _mixins.scss      # Responsive media query mixins
│   ├── _normalize.scss   # Base styles
│   └── main.scss         # Main stylesheet entry point
└── index.html            # Main HTML page
```

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm

### Installation

**1. Clone the repository:**

```bash
git clone https://github.com/santana1719/MET-landing-portfolio.git
```

**2. Navigate to the project directory:**

```bash
cd MET-landing-portfolio
```

**3. Install dependencies:**

```bash
npm install
```

**4. Start the development server:**

```bash
npm start
```

**5. Open the local URL displayed in your terminal.**

## Available Scripts

- `npm start` — start the development server.
- `npm run build` — create a production build.
- `npm run lint` — run configured code checks.
- `npm test` — run linting and configured tests.
- `npm run deploy` — deploy the project using the configured deployment script.

## Design Reference

The landing page was developed based on the following Figma design:

[The MET — Figma Design](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)

## Key Learnings

During this project, I practiced:

- Converting a Figma design into a responsive webpage.
- Writing semantic HTML and organizing page sections.
- Structuring SCSS using the BEM naming convention.
- Creating reusable mixins and media queries.
- Implementing interactive navigation without JavaScript.
- Working with CSS transitions, hover states, and responsive backgrounds.
- Building and deploying a frontend project with Parcel and GitHub Pages.

## Disclaimer

This is an unofficial educational project created for learning and portfolio purposes. It is not affiliated with The Metropolitan Museum of Art.

Exhibition details are static and based on the original design. The contact form is for demonstration purposes only and does not send messages to a server.
