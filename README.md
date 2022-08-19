# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
N.B.: I haven't learned yet how to adapt to device's screen size -> this solution is only for Desktop layout for now
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Repository URL: [https://github.com/windu80/Frontend-challenge01](https://github.com/windu80/Frontend-challenge01)
- Live Site URL: [https://windu80.github.io/Frontend-challenge01/](https://windu80.github.io/Frontend-challenge01/)

## My process

### Built with

- Sublime Text (code editor for HTML and CSS)
- Paint to sample the colors
- CSS Grid
- Help of Chrome Dev Tools and Pesticide extension (to view all components in boxes)

### What I learned

- Use body with "display: table" and a div container with "display: table-cell" and then I can use the property "vertical-align: middle" to center vertically (making sure the body and html and parent-containers occupy 100% of the space)
- Removing table and tbody -> "border-spacing: 0" in the table element
- Change the color of an svg element: edit and use the "fill" in the "path" tag
- Round corners with "border-radius" property
- Anchor tag which opens in a new tab:
```html
<a href="https://github.com/windu80/" target="_blank">windu80</a>
```
- "letter-spacing" property
- "font-weight" property
- "text-decoration: line-through;"
- Remove the default 4px between inline-block elements -> font-size: 0 to the parent element, and then declare a font-size on the children (https://stackoverflow.com/questions/5078239/how-to-remove-the-space-between-inline-inline-block-elements)


### Useful resources

- [IconScout](https://iconscout.com/) - I found a good cart SVG icon there.
- [Google Fonts](https://fonts.google.com/) - To get the Montserrat and Fraunces fonts.
- [MDN]
- [W3schools]
- [Stackoverflow]
