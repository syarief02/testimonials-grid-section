Below is a complete **README.md** based on your template, filled out for your Testimonials Grid Section solution. You can save this as `README.md` at the root of your project.

---

# Frontend Mentor - Testimonials Grid Section Solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)

- [My process](#my-process)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the testimonials grid depending on their device’s screen size.
- Experience a seamless transition from a single-column mobile layout to the complex 4-column desktop layout with specific cards spanning multiple grid areas.

### Screenshot

![Desktop Screenshot](./Capture.PNG)
_Desktop view at 1440px width._

### Links

- Solution URL: [https://github.com/syarief02/testimonials-grid-section](https://github.com/syarief02/testimonials-grid-section)
- Live Site URL: [https://syarief02.github.io/testimonials-grid-section/](https://syarief02.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic **HTML5** markup&#x20;
- **CSS custom properties** for theming&#x20;
- **CSS Grid** with `grid-template-areas` for layout&#x20;
- **Flexbox** for author header alignment&#x20;
- **Mobile-first workflow**
- `filter: drop-shadow()` for true drop shadows&#x20;

### What I learned

- Using CSS Grid’s **named areas** to craft a 4-column desktop layout where cards span multiple rows/columns seamlessly.
- The distinction between `box-shadow` and `filter: drop-shadow()`, and why `drop-shadow` better respects border-radius.
- Layering decorative SVG pseudo-elements behind text, then pulling specific elements (the summary `<h2>`) forward via `z-index`.
- Strictly following a style guide: matching exact HSL color tokens and a 13px base typography scale .

### Continued development

- Add JavaScript toggles for **light/dark modes**.
- Improve **accessibility**: ARIA labels, keyboard navigation hints, and screen reader testing.
- Explore **SVG icon animations** for subtle interactive feedback on hover.

### Useful resources

- [CSS-Tricks: A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) – deep dive into grid concepts.
- [MDN: filter() — drop-shadow()](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow) – how to use and fine-tune drop shadows.
- [Frontend Mentor Challenge](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) – original prompt.

## Author

- GitHub – [@syarief02](https://github.com/syarief02)
- Frontend Mentor – [@syarief02](https://www.frontendmentor.io/profile/syarief02)

## Acknowledgments

- Big thanks to **Frontend Mentor** for providing this challenge and detailed style guide.
- Shout-out to **CSS-Tricks** for Grid and `drop-shadow` insights.

---

_README structure adapted from the Frontend Mentor template_ .
