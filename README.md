# What the flexbox

This is my solution to the [What the flexbox](https://flexbox.io). This tutorial helped me learn Flexbox the right way, and it also changed how I align items.

## Table of contents

  - [Overview](#overview)
    - [Some information](#some-information)
    - [Examples on what you will make](#examples-on-what-you-will-make)
    - [Link](#link)
  - [My process](#my-process)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments and source](#acknowledgments-and-source)
 

## Overview

### Some information
The first 13 videos are aimed at understanding the fundamentals of Flexbox, like understanding rows, columns, axes, wrapping centering and etc. The last 7 are coding tutorials which you can follow along. In the last 7 you will make things like a mobile app layout, a form, a pricing grid and much more. I only hosted the last 7, because the others are just there for practice. 

### Examples on what you will make
Mobile app layout:

![Desktop](.design/screenshot.jpg)

Pricing-grid:

![Pricing-grid](.design/screenshot.jpg) 
Form:

### Link

- Live Site URL: [My live site](https://purplehippo911.github.io/flexbox/)

## My process

### What I learned
I learned how to align content and items, and I and how to make your site a bit more responsive. I learned about axes, columns,rows, orders and much more. 

```html
        <div class="plan plan1">
        <h2>Cat</h2>
        <p>Common, yet regarded by many as the worst house pet.</p>
        <ul class="features">
          <li>Scratches everything</li>
          <li>Easily lost for days</li>
          <li>Kind of a bummer</li>
        </ul>
        <p class="price">free</p>
        <a href="#" class="cta">😾 Really?</a>
      </div>
        ......
       <div>
    ```

```css
  .app-wrap {
    display:flex;
    flex-direction:column;
   }

  .app-wrap > * {
  flex:1 1 auto;
  }

  .content {
    overflow-y:scroll;
    -webkit-overflow-scrolling:touch;
   }

  .app-header {
    display:flex;
    align-items:center;
    justify-content: space-around;
   }

   .icon-bar {
     display:flex;
    }
    .icon-bar a {
     flex:1;
    }
```

### Continued development
I am planning on making my own little webisite, so be tuned in for that. I will also try to get more comfortable with flexbox (and JS), but after that I'm planning on learning Grid and probably react.   

### Useful resources

- [CSS tricks](https://www.youtube.com/watch?v=TAB_v6yBXIE&t=436s&ab_channel=KevinPowell) - This is an extra resource which has a downloadable cheatsheet for flexbox, which is good for recap.  
 
## Author

- Frontend Mentor - [@purplehippo911](https://www.frontendmentor.io/profile/purplehippo911)
- Github - [@purplehippo911](https://www.github.com/purplehippo911)


## Acknowledgments and source

Huge thanks to [Wes Bos](https://wesbos.com) for creating  this free tutorial. And thanks to you for checking out my repository. 

And HAPPY CODING!🎆🍙🍕🧨🧶🧶🛒👓 
                                                                
