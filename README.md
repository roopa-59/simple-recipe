# Frontend Mentor - Recipe Page Solution

This is my solution to the **Recipe Page** challenge on Frontend Mentor. The goal of this project was to recreate the provided design using semantic HTML and CSS while following a mobile-first, responsive approach.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- View the recipe page with a responsive layout.
- See an optimized layout for different screen sizes.
- Read recipe details with clear typography and spacing.
- View styled lists, tables, and sections matching the provided design.

### Screenshot

![Recipe Page Screenshot](./screenshot.png)


### Links


- **Live Site URL:** https://roopa-59.github.io/simple-recipe/

---

## My Process

### Built With

- Semantic HTML5
- CSS3
- Flexbox
- Mobile-first workflow
- Responsive Design
- Google Fonts (Young Serif & Outfit)

---

### What I Learned

During this project, I improved my understanding of:

- Writing semantic HTML for better accessibility.
- Building responsive layouts using a mobile-first approach.
- Using Flexbox to structure page content.
- Styling lists using `::marker`.
- Creating clean tables with `border-collapse`.
- Using `max-width` together with percentage widths for responsive cards.
- Applying consistent spacing using padding, margins, and line-height.
- Organizing CSS for better readability and maintenance.

One CSS technique I found particularly useful was making the card responsive:

```css
.card {
    width: 90%;
    max-width: 736px;
    margin: 2rem auto;
}
```

I also learned how to style ordered list numbers using the `::marker` pseudo-element:

```css
ol li::marker {
    color: hsl(14, 45%, 36%);
    font-weight: bold;
}
```

---

### Continued Development

In future projects, I want to continue improving my skills in:

- CSS Grid
- Responsive layouts for tablets and large screens
- Accessibility (ARIA attributes and keyboard navigation)
- CSS animations and transitions
- Writing cleaner and more reusable CSS

---

### AI Collaboration

I used **ChatGPT** during this project to assist with learning and debugging.

It helped me:

- Understand responsive design concepts.
- Learn when and why to use `max-width`.
- Style HTML tables and lists.
- Improve spacing and typography.
- Better understand Flexbox alignment.
- Debug CSS layout issues.
- Follow best practices while recreating the Frontend Mentor design.

Rather than generating the entire solution, I used AI as a learning assistant to understand concepts and improve my implementation.

---

## Author

**Roopalakshmi V**

- GitHub: https://github.com/roopa-59

---

⭐ This project was completed as part of the **Frontend Mentor** challenges to improve my HTML, CSS, and responsive web design skills.