# Changelog

# [Part 2: Visuals, Responsive Design & UX Refactor] - September 2026

# What was Added
- **Centralized Stylesheet (`style.css`):** Created a comprehensive external CSS file defining CSS custom variables (`--primary-brown`, `--soft-pink`, `--warm-butter`, `--bg-cream`) for a unified aesthetic.
- **Responsive Layout Grids:**
  - Integrated CSS Grid (`repeat(auto-fit, minmax(...))`) for the product showcase on `Products.html` and the reviews section on `testimonials.html`.
  - Implemented CSS Flexbox for responsive navigation bars and header layouts.
- **Media Queries:** Added breakpoint rules (`@media (max-width: 600px)`) allowing mobile navigation stacking and single-column card flows on smaller screens.
- **Accessibility Enhancements:** Added semantic HTML5 landmarks (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`) and explicit `<meta name="viewport">` tags across all HTML pages.

# What wasChanged
- **Typography & Styling:** Replaced deprecated HTML tags (`<font>`, `<center>`, `bgcolor`, and border attributes) with clean, maintainable CSS typography rules and spacing.
- **Navigation Usability:** Standardized navigation links across all pages (`Home`, `About Us`, `Products`, `Enquiry`, `Testimonials`, `Contact Us`) with enlarged touch targets and hover states.
- **Call-to-Action Buttons:** Restyled standard browser buttons into consistent, rounded interactive CTA buttons (`.btn`) with elevation hover effects.

# What I Removed
- Removed legacy `<table>`-based positioning layouts used for spacing and structure, replacing them with modern responsive Flexbox and Grid containers.
- Removed hardcoded inline color formatting.



Assignment Feedback & Implementation Report: Sweet Crumbs Bakery
Project: Sweet Crumbs Bakery Web Platform
Component: Part 2- Designing the Visuals, Responsive Design & UX Refactor
Date: September 2026
1. Executive Summary
Sweet Crumbs Bakery has undergone a major visual and architectural overhaul by changing its old HTML-based design features to a modular external CSS style sheet (style.css). The headers, menus, and footers on all the pages (homepage.html, About Us.html, Products.html, Contact.html, testimonials html, and Contact Us.html) have been made uniform so that there exists aluniform brand image.
Responsive design techniques were applied in the use of CSS Grid, Flexbox, media queries, and relative size measuring units to ensure smooth design across all kinds of devices - mobile phones, tablets, and computers. There were made steps to improve the design with the help of new card layout design techniques, improved typographical hierarchy, and drop shadow effects and engaging hover effects. implementation integrity.


2. Core Areas of Enhancement
* Separation of Concerns & Code Maintainability: Removed deprecated HTML presentation tags including<font>, <center?, and bgcolor attributes. Eliminated nested layout <table> elements previously used for alignment and positioning, migrating all structural styling into an external CSS file (style.css).
* Visual Consistency & Branding: Unified color tokens via CSS custom variables (--primary-brown: #6B3E26, --soft-pink: #FADADD, --warm-butter: #F5E1C8, --bg-cream: #FFFEE. Standardized the global header and footer structures to ensure identical branding and seamless transitions between pages.
* Modern Layouts & User Experience (UX): Replaced rigid table columns on Products.html and testimonials.html with responsive card-based CSS Grid components. Enhanced interactivity with hover elevations (transform: translateY(-4px)) and styled touch-friendly call-to-action buttons (.btn).
Documentation & Verification: Created an entry in the repository's README.md under the changelog section detailing each design phase, structural migration, and accessibility improvement.

3. Technical Implementation & Responsive Standards
   * Breakpoints & Adaptive Layouts: Defined standard device breakpoints for desktop, tablet, and mobile interfaces. Media queries stack multi-column grids and navigation lists into accessible vertical flows on screen widths under 600px.
   * Fluids Units & Scalability: Applied relative units (rem, em, %) across typography, container max-widths, and padding modules to support dynamic browser zooming and layout flexibility.
   * Responsive Asset Management: Standardized asset constraints across all product photography and branding imagery (max-width: 100%; height: auto;) to prevent viewport horizontal overflow.

     3. Technical Implementation & Responsive Standards
  
   


