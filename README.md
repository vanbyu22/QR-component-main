# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### Screenshot

![Final Result](https://github.com/vanbyu22/QR-component-main/blob/464c778594712cbdab21f2d94a1b83a20749b386/Screenshot_15-3-2025_updated.jpeg)


### Links

- Challenge URL on Frontend Mentor: (https://www.frontendmentor.io/learning-paths/getting-started-on-frontend-mentor-XJhRWRREZd/steps/67d58cc4e22457629b6cff0b/challenge/start)

## My process

Gathering what I've learned from various sites and tutorial videos, I started by laying out the design semantically. It only consists of a "Main" and "Footer" sections.

I originally had the attribute part of the main container but I decided to turn it into a sticky/fixed footer.

```html
  <footer class="footer">
    <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="https://github.com/vanbyu22/" target="_blank">Vanessa B. Yu,</a> 2025.
    </div>
  </footer>
  ```

```css
footer {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    background-color: hsl(216, 15%, 48%);
    color: white;
    text-align: center;
 }
 ```

### Built with

- Semantic HTML5 & CSS on VS Code

### What I learned

While this is not my very first project, I have finally learned how to write semantic and cleaner code. I realized that less is more.

As for Github, I'm still figuring it out. It took way too long to set up this little repository but I am happy to finally put out work with feeling the need for it to be "complete" or "correct". Please feel free to give tips, critiques, and corrections. Always willing to learn.

### Continued development

- Continue to learn and problem solve.
- Joining groups to collab, critique, and network with.
- Continue to figure how to work Github.

### Useful resources

- [LearnFrontendNow](https://www.learnfrontendnow.com/) - Shout to Harry for inspiring me to take up coding again.
- [W3Schools](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_fixed_footer) - The code for the sticky/fixed footer.



## Author

For now it's just this Github, will update and add more later.

