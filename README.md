# Portfolio Template Project

A clean portfolio landing page built with semantic HTML, modern CSS, and a structured SCSS workflow. This project showcases a personal portfolio design with hero content, case studies, testimonials, recent work, and a contact section.

## Original Design Reference

The original layout concept is available in the project images folder:

- `images/Original-figma-design.png`

This image represents the design inspiration used to create the page structure and visual styling.

## Project Structure

- `index.html` — main portfolio page markup
- `styles/main.css` — compiled stylesheet used by the page
- `styles/main.scss` — source SCSS entry file
- `styles/abstracts/_variables.scss` — SCSS color and spacing variables
- `styles/abstracts/_mixins.scss` — reusable SCSS flexbox mixins
- `styles/abstracts/_base.scss` — base reset and global typography styles
- `images/` — original design and image assets used throughout the layout

## Concepts Used

### HTML & Layout

- Semantic HTML5 sections: `header`, `main`, `section`, `footer`
- Navigation with anchor links for page sections
- Content sections for:
  - Hero / introduction
  - Case studies
  - Testimonials
  - Recent work
  - Contact form
- Use of accessible image `alt` attributes and button controls

### CSS & Styling

- Global reset with `box-sizing: border-box`
- Smooth scrolling with `scroll-behavior: smooth`
- Color theming using black/white contrast and accent button colors
- Layout built primarily with `display: flex` and flexible containers
- Spacing utilities for padding and margin classes (`p-1`, `pt-1`, `mr-2`, etc.)
- Object-fit image styling for responsive profile and work images
- Responsive width constraints with `max-width`, `width: 90%`, and centered content

### SCSS Concepts

- Variables for colors and spacing:
  - `$primary-color`
  - `$secondary-color`
  - `$space`
- Mixins for reusable layout patterns:
  - `@mixin flex-container`
  - `@mixin flex-gap`
- Loop-based utility generation using `@for` to create padding and margin helpers
- Partial organization:
  - `_variables.scss`
  - `_mixins.scss`
  - `_base.scss`
- Modular SCSS import structure from `main.scss`

## Visual Sections

- **Hero section** with profile image, introduction, call-to-action button, and partner logos
- **Case Studies** with project cards and call-to-action buttons
- **Testimonials** using quote cards and client previews
- **Recent Work** display cards for portfolio examples
- **Contact section** with email, phone, and message fields
- **Footer** with centered branding text

## How to View

1. Open `index.html` in your browser.
2. Review `images/Original-figma-design.png` for the original design reference.
3. Edit `styles/main.scss` to update colors, spacing, or layout patterns.

## Notes

- The repo includes both source SCSS (`styles/main.scss`) and compiled CSS (`styles/main.css`).
- The homepage is static and does not require a server to view.
