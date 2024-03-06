## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./images/Screenshot.jpg)

### Links

- Solution URL: [Link to the Github repository](https://github.com/softwaredev-sk/qr-code-design-replica)
- Live Site URL: [Live Site](https://softwaredev-sk.github.io/qr-code-design-replica)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- VSCode

### What I learned

- Using this challenge, I learned how to contain images within a div container of varying sizes.
- I learned to use box-shadow for a very minimal shade of background shadow.
- Learnt how to add breakpoints for different device dimensions
- Learnt to replicate the design by looking at the picture and picking the details from it.

```css
.qr-code {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.child-container {
  box-shadow: 1px 1px 100px -40px #a0a8b1;
}
```

### Continued development

Further, I will be building a dynamic QR generator that can generate a QR code based on user input and it can be captured to share with other users.

### Useful resources

- [MDN Documentation of box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - It helped me implement box-shadow which adds beauty to the div container without being obvious that there is a shadow behind the container.

## Author

- Website - [Shailendra Kumar](https://www.shailendra.xyz)
- Frontend Mentor - [@softwaredev-sk](https://www.frontendmentor.io/profile/softwaredev-sk)
- X (Formely Twitter) - [@shailendrakrsk\_](https://www.twitter.com/shailendrakrsk_)

## Acknowledgments

A special thanks to Frontend Mentor for providing design ideas to practice coding. Challenges from the frontendmentor are helping me to restart my frontend development journey again, but now in a structured way.
