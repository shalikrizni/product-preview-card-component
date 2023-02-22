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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

- Mobile View: ![Alt text](Screenshots/My%20Mobile%20View.png)
- Desktop View: ![Alt text](Screenshots/My%20Desktop%20View.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

After learning the basics of HTML and CSS, I took on a challenge to test my skills. At first, I wasn't sure how to begin or approach the challenge, so I turned to YouTube videos for guidance. With the help of these resources, I was able to develop the project successfully.

Later, I decided to attempt the challenge again, but this time without relying on any external resources. Through this process, I gained a deeper understanding of CSS custom properties, and I learned how to practically apply CSS grid and flexbox to my projects. I also developed the skill of thinking critically and creatively to solve problems and approach web design from a mobile-first perspective. Overall, the experience helped me to become a more confident.

some of the new code snippets I used which I am new to it, see below:

```html
<source srcset="images/image-product-desktop.jpg" media="(min-width: 600px)">

<button class="button" data-icon="shopping-cart">Add to Cart</button>
```

```css
.button[data-icon="shopping-cart"]::before{
    content: '';
    background-image: url(images/icon-cart.svg);
    width: 15px;
    height: 16px;
}

.button:is(:hover, :focus){
    background-color: var(--clr-darker-cyan);
}
```

### Continued development

I am planning to use CSS custom variables, as well as other styling techniques such as CSS flexbox and grid, to approach and solve problems in my future projects and challenges. These techniques will allow me to design websites more efficiently and creatively.

By utilizing CSS custom variables, I will be able to define and reuse common values throughout my project, making it easier to update styles and maintain consistency. Additionally, the use of CSS flexbox and grid will enable me to create responsive layouts that adapt to different screen sizes and devices.

Overall, I am confident that by employing these techniques and methodologies, I will be able to approach web development with a more structured and efficient mindset, leading to better and more innovative designs.

### Useful resources

- Taking on a Frontend Mentor challenge | Responsive Product Preview Card Component by Kevin Powell 
(https://youtu.be/B2WL6KkqhLQ) - This helped me to learn how to approach for the challenge and the overall solution.


## Author

- Frontend Mentor - [@shalikrizni](https://www.frontendmentor.io/profile/shalikrizni)
- LinkedIn - [@Shalik Rizni] (https://www.linkedin.com/in/shalikrizni/)



## Acknowledgments

First and foremost, I would like to express my gratitude to Mr. Kamran Ahamed for introducing me to roadmap.sh. Currently, I am following the roadmap with the hope of becoming a full-stack developer one day. The roadmap has been instrumental in helping me acquire the necessary skills to get started with HTML and CSS. I plan to return to the roadmap to learn the other essential skills required to complete my journey.

I would also like to thank Mr. Kevin Powell, who is a renowned CSS expert, for his videos that have been immensely helpful to me in many ways. Furthermore, I would like to express my heartfelt thanks to my parents and friends for their constant support and encouragement.

There is still a long way to go, but I am excited about the journey and look forward to learning more and growing as a developer.

