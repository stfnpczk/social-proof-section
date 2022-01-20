# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

<br>

![](./design/desktop-preview.jpg)


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Iterations](#iterations)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size


### Links

- [Frontend Mentor - solution URL](https://www.frontendmentor.io/solutions/social-proof-section-built-with-scss-and-flexbox-6QBCuq8xm)
- [Live Demo](https://stfnpczk.github.io/social-proof-section/)

## My process

### Built with

- Semantic HTML5 markup
- BEM notation
- Flexbox
- Mobile-first workflow

### What I learned


- `&:nth-child(n)` : indent single items in a flex flow


```scss
 &:first-child {
  align-self: start;
 }

 &:nth-child(2) {
  align-self: center;
 }

 &:nth-child(3) {
  align-self: end;
 }
```

### Iterations
Implementing the indentation with `n-th-child(n)` is perhaps not the best way of doing it. I might try a grid layout instead.

## Author
- Frontend Mentor - [@stfnpczk](https://www.frontendmentor.io/profile/stfnpczk)

