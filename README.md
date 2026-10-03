# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Links

- Solution URL: https://github.com/roba365/qr-code-component
- Live Site URL: https://roba365.github.io/qr-code-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox (centering layout and component structure)
- Mobile-first responsive design (`max-width`)

### What I learned

During this project, I strengthened my understanding of centering elements using Flexbox and managing CSS box alignment. I also learned how to handle default browser spacing using global resets, make components responsive using `max-width`, and use `rem` units for accessible font scaling.

```html
<main class="card">
  <img src="./images/image-qr-code.png" alt="QR code leading to Frontend Mentor website">
  <div class="card-text">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</main>
```

```css
body {
  font-family: "Outfit", sans-serif;
  background-color: hsl(212, 45%, 89%);
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.card {
  display: flex;
  flex-direction: column;
  gap: 24px;
  background-color: hsl(0, 0%, 100%);
  max-width: 320px;
  width: 100%;
  padding: 16px 16px 40px 16px;
  border-radius: 20px;
}

h1 {
  font-size: 1.375rem;
  line-height: 1.2;
}

p {
  font-size: 0.9375rem;
  line-height: 1.4;
}
```

### Continued development

In future projects, I want to continue refining:
- Responsive design patterns using CSS Grid alongside Flexbox
- Standardized Git workflow habits and commit structures
- Typography spacing and fluid text scaling

### AI Collaboration

Used Gemini as a thought partner and technical debugging guide to:
- Establish a clean Git commit workflow and schedule.
- Debug DevTools box-model overlays to identify and remove redundant margins.
- Optimize CSS layout spacing by leveraging Flexbox `gap` and `max-width` responsiveness.

## Author

- Frontend Mentor - [@roba365](https://www.frontendmentor.io/profile/roba365)
- GitHub - [@roba365](https://github.com/roba365)
