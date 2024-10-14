# Amazon Clone

This project is a simple clone of the Amazon website, built using only HTML and CSS, with some additional animations to enhance the user experience.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Animations](#animations)
- [Folder Structure](#folder-structure)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

## Overview
This project replicates the basic layout and design of the Amazon home page. It focuses on styling and layout using CSS, with various animations for smoother transitions. While it doesn’t include any backend functionality, it provides a visually appealing user interface with core elements like navigation bars, product listings, search bars, and footer sections.

## Features
- **Responsive Design:** The clone is fully responsive and works on multiple screen sizes.
- **Navigation Bar:** A sticky top navigation bar with Amazon-style links, logo, and search bar.
- **Product Listings:** Grid-based product display with hover animations.
- **Footer:** A simple footer that mimics Amazon’s design.
- **Basic Animations:** Hover effects, button animations, and transitions.
  
## Tech Stack
- **HTML5**
- **CSS3**
  
## Animations
We’ve included a few simple but effective animations using CSS:
- **Hover Animations:** When hovering over product items, they scale up slightly for emphasis.
- **Button Animations:** Buttons in the navigation bar and product cards have hover effects to improve interactivity.
- **Smooth Scroll:** Internal links provide a smooth scrolling effect to improve user experience.
  
Example of a hover animation on product cards:
```css
.product-card:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}

