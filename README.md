# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development]
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview


### Links

- Solution URL: [https://github.com/theabernardo/frontend-qrcode]


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Google Fonts and Colors)
- Flexbox (For centering the layout)
- Fluid design principles using flexible spacing

### What I learned

During this project, I mastered the core concepts of centering elements using Flexbox. I learned how to perfectly center a component both horizontally and vertically on the viewport by applying `display: flex`, `justify-content: center`, and `align-items: center` to the body element along with `min-height: 100vh`. 

I also gained a solid understanding of the CSS Box Model, specifically the behavioral difference between `padding` (inner spacing) and `margin` (outer spacing). Furthermore, I discovered how `max-width` creates highly flexible layouts compared to fixed `width` properties, allowing my card component and images to scale responsively even down to smaller screens like `320px`. Lastly, I learned the correct syntax for applying clean, soft `box-shadow` values using `rgba` transparency without syntax errors.

```

```
```css
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.card  {
   box-shadow: 10px 30px 25px 5px rgba(3, 3, 3, 0.05);
}

```

### Continued development

In my future frontend projects, I plan to focus on:
- Practicing Flexbox on more complex layouts like navigation bars and grids.
- Exploring CSS Grid layout mechanics for large-scale page sections.
- Deepening my knowledge of responsive web design across multiple device breakpoints.




### AI Collaboration

- Tool Used - Claude (via Frontend Mentor AI Assistant)
- Usage Mode - AI Mentorship / Step-by-Step Learning Partner
- How I used it - I used the AI to understand the logic behind CSS Flexbox, the Box Model (padding vs margin), and how to read browser DevTools for responsiveness. Instead of asking for complete copy-paste code solutions, I asked the AI to explain concepts, guide my decision-making, and check my syntax errors.


## Author

- Frontend Mentor - [@theabernardo](https://www.frontendmentor.io/profile/theabernardo)



