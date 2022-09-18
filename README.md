# Frontend Mentor - QR code component solution

See down

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Netlify](https://fronted-mentor-qr.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned


Semantic labels:

```html
<div class="card">
    <figure class="card__figure">
      <img src="./images/image-qr-code.png" alt="QR code" class="card__figure--image">
      <figcaption class="card__figure--caption">Improve your front-end skills by building projects</figcaption>
    </figure>
    <p class="card__text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
```

Variables _CSS_ and __grid__

```css
.card{
    display: grid;
    padding: 15px;
    max-width: var(--max-width);
    text-align: center;
    background-color: var(--bg-card);
    border-radius: 1.5em;
}
```

## Author

- Website - [WebFerrol](https://webferrol.github.io)