# 💻 CS World — Computer Science Website

A multi-page website built with **HTML**, **CSS**, and **JavaScript** as part of a Web Services Design laboratory assignment at **Politechnika Bydgoska**.

The theme is **Computer Science** — covering algorithms, data structures, programming languages, and AI.

---

## 📁 Project Structure

```
├── index.html       # Home page
├── subpage.html     # Topics page
├── contact.html     # Contact page
├── styles.css       # Main stylesheet (shared)
└── contact.css      # Contact page specific styles
```

---

## ✨ Features

### Pages
- **Home** — Introduction to Computer Science with text, image, and external links
- **Topics** — Algorithms, data structures, numbered list, and a programming languages comparison table
- **Contact** — Contact info, contact form, and a JavaScript welcome prompt

### HTML
- Semantic structure with `<nav>`, `<header>`, `<main>`, `<footer>`
- Three paragraphs with **bold** and *italic* text
- Images using `<img>` tag
- External links to [CS50](https://cs50.harvard.edu) and [LeetCode](https://leetcode.com)
- Numbered list and table with merged cells (`colspan` + `rowspan`)
- Navigation between all three pages
- Contact form with text inputs, radio buttons, checkbox, submit and reset

### CSS
- CSS custom properties (variables) for consistent theming
- Background color and header font color customization
- `.active` class to highlight current page in navigation
- `.right` class using `float: right` for image positioning
- `img:hover` — opacity change and cursor style
- `p::first-letter` pseudo-element on subpage paragraphs
- Table with 2px black cell borders and 5px colored outer border
- Media query: table hidden on screens narrower than 600px
- Separate `contact.css` with a distinct visual style

### JavaScript
- Dark mode / Light mode toggle buttons
- Automatic date in footer
- `prompt()` on contact page — asks for user's name and displays a welcome message

---

## 🚀 How to Run

No build tools or dependencies needed.

1. Clone the repository:
   ```bash
   git clone (https://github.com/umutilhann/Web-Services-Design.git)
2. Open `index.html` in your browser.

> All pages link to each other via the navigation bar. Internet connection is required for Google Fonts and Unsplash images.

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript

---

## 📚 Assignment

**Course:** Web Services Design  
**Institution:** Politechnika Bydgoska — Wydział Telekomunikacji, Informatyki i Elektrotechniki  
**Score:** 25 points total

---

## 📄 License

This project was created for educational purposes.
