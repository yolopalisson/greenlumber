# Green Lumber Holdings - Website Redesign

A modern, high-performance, and fully responsive redesign of the Green Lumber Holdings website. 

This project is built as a **single-page, zero-dependency application** using modern HTML5, CSS3, and Vanilla JavaScript. It is designed to be lightweight, highly accessible (WCAG compliant), and visually striking, utilizing a corporate Glassmorphism aesthetic.

## 🚀 Key Features

*   **Glassmorphism UI:** Frosted-glass navigation and floating overlays for a premium, modern feel.
*   **Mobile-First Architecture:** Flawless responsiveness across all devices. Includes a custom mobile hamburger menu and optimized touch targets.
*   **Zero Dependencies:** No jQuery, Bootstrap, or external animation libraries. Pure CSS and Vanilla JS for maximum performance.
*   **Interactive Image Modals:** Gallery, hero, and service images can be clicked to expand into a full-screen lightbox with keyboard focus trapping.
*   **Dynamic Testimonial Carousel:** Swipeable, scroll-snap testimonial section with manual arrow controls and dynamic pagination dots.
*   **Animated Stats:** Intersection Observer-driven count-up animations for the company's key metrics.
*   **WhatsApp Integration:** Persistent floating WhatsApp button and direct CTA links for seamless lead generation.
*   **Active Navigation Pill:** A scroll-spy navigation system that highlights the current section with a solid brand green pill.
*   **SEO Optimized:** Includes LocalBusiness JSON-LD structured data schema for improved local search visibility.
*   **WCAG Compliant:** High contrast ratios, keyboard navigability, focus management, and `prefers-reduced-motion` support.

## 🛠️ Tech Stack

*   **HTML5:** Semantic markup.
*   **CSS3:** CSS Custom Properties (Variables), Flexbox, CSS Grid, `backdrop-filter`, `clamp()` for fluid typography.
*   **Vanilla JavaScript:** Intersection Observers, DOM manipulation, and event listeners (No external libraries).
*   **Typography:** [Outfit](https://fonts.google.com/specimen/Outfit) (Headings) & [Inter](https://fonts.google.com/specimen/Inter) (Body) via Google Fonts.

## 📁 Project Structure

Since this is built as a unified file for simplicity and performance, the entire site lives in one file:

```text
/
├── index.html       # Contains HTML, inline CSS, and inline JS
└── README.md        # Project documentation
