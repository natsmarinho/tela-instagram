## Table of contents

- Overview
  - The challenge is to build out the initial page of the instagram and get it looking as close to the design as possible.
  - My process: It took me 4 hours to build this.
  - Built with: HTML5 and CSS3.
  - What I learned: I've learned how to use space-evenly on display flex, border transparent, background-size: cover and more about responsivity. 
  - Continued development: I have to continue practice how to use the responsive page. 
- Author: Natali Marinho. 
- Acknowledgments: css and html.


### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See my profile on instagram

### Screenshot

![](./imagens/readme-pic.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned


```css
  .grupo{
       border: 1px solid transparent;
   }
```
```css
.grupo{
    background-size: cover;
    justify-content: space-evenly;
}
```
```css
@media(max-width: 1024px){
    body{
        background-color: #ffffff;
    }
    .instagram-wrapper{
        width: 90%;
    }
}

@media(max-width: 650px){
    .instagram-wrapper{
        width: 90%;
    }
    .phone{
        display: none;
    }

   .log{
       width: 100%;
   }
   
   .grupo{
       border: 1px solid transparent;
   }
}
```
### Continued development

I want to continue learn about resposivity and more about javascript.

## Author
- Twitter: [@friidakhlo](https://www.twitter.com/friidakhalo)
- Instagram: [@natsmarinho](https://www.instagram.com/natsmarinho) 
- Linkedin: [@natsmarinho](https://www.linkedin.com/in/natsmarinho/)
