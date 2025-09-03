## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- position
- pseudo-elements

### What I learned

in this project i used some CSS properties to help for responsive font size, such as @media
and pseudo-elements

To see how you can add code snippets, see below:

main {
display: flex !important;
width: 800px;
height: 600px;
flex-direction: column;
justify-content: center;
align-items: center;
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
}
main::before {
content: "";
width: 600px;
height: 600px;
background-image: url(../images/bg-pattern-top.svg);
background-size: cover;
position: absolute;
top: -60%;
left: -45%;
transform: scale(1.4) rotate(353deg);
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements

### Useful resources

- [w3schools] https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
