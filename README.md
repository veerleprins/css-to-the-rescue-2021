# Russ & Daughters - Menu card

## CSS to the Rescue @cmda-minor-web 2020 - 2021

<img width="1624" alt="Screenshot of the page." src="https://user-images.githubusercontent.com/35265583/109835968-00ebb600-7c44-11eb-96d5-38d1bbb968d4.png">

## Table of contents:

- [Description](#black_nib-description)
- [Feature](#small_orange_diamond-feature)
- [Datasets](#link-datasets)
- [Install](#arrow_down-install)
- [GitHub Pages](#globe_with_meridians-github-pages)
- [Techniques](#star-techniques)
- [Log](#page_with_curl-log)
- [Sources](#books-sources)

## :black_nib: Description

For the CSS to the Rescue course within the Minor Web Design & Development ([@cmda-minor-web](https://github.com/cmda-minor-web)) we learn more about the many possibilities of CSS. Everything that is made is built with only HTML and CSS.

This repository shows the project in which I transform the simple HTML structure of a **menu for a restaurant** into a beautiful web page. Here are a number of points that have been incorporated on the web page:

**Context:**

- Print-stylesheet

**Restrictions:**

- Two colors
- Responsive without media queries

To read the full process you can have a look at my [Log](#page_with_curl-log).

## :globe_with_meridians: Github Pages

My webpage can be found at the link below:

https://veerleprins.github.io/css-to-the-rescue-2021/

## :star: Techniques

Techniques that I have learned / that I have improved myself in:

- @media print
- keyframes {}
- clamp()
- skewY()
- filter()
- gradients()
  - radial
  - linear
  - repeating-linear
- SVG filters
  - feDropShadow
  - feColorMatrix
  - feGaussianBlur

## :page_with_curl: Log

### Week 4 (Deadline)

Since I didn't feel like I had made much within CSS in the first weeks, I decided to spend two more days on CSS during the holidays to make something extra. During the progress meeting with Sanne, it was therefore decided to make something with SVG filters on my site. I have never worked with SVG filters myself and had no idea what to do with them. I was also not at this theme session and found it difficult to get started.

#### What went wrong

What I found very difficult myself was finding out how svg filters actually worked. I have not really tested on codepen, but immediately dived into my CSS itself. For this reason I don't have any experiments really.

#### What went right

What went well is that I decided to make an extra planet with the help of yes, again gradients. But this time I put svg filters on this. For example, I have used feMatrixColor, feDropShadow and feGaussianBlur. Below I have posted a screenshot of my new planet that I made using SVG filters:

<img width="371" alt="Screenshot of the planet on my page." src="https://user-images.githubusercontent.com/35265583/109834088-1cee5800-7c42-11eb-804f-2315c61ad1b2.png">

I also made a favicon to stay in the space theme of my website.

### Week 3

In this week we already had the last guest lectures and theme sessions. The guest lecture by **Olivia Ng** inspired me to learn that you can do so much with a background-image selector! She gave examples where people made a whole illustration using literally one div and the selector background image. I was really impressed by this and it seemed interesting to me to get started.

For this reason, I followed **three theme sessions** this week instead of two. My chosen theme sessions were: **Custom Properties**, **@media print** & **Gradients**.

Based on the guest lecture and the theme sessions, I then decided to make a moon with the property background image. I also decided to work more with background images on my site.

#### What went wrong

My first versions of making a moon didn't quite go the way I wanted. I didn't know exactly how to use the gradients to make a good moon. This was my first version:  
[Moon version 1](https://codepen.io/veerleprins/pen/BaQVmPd)
[Moon version 2](https://codepen.io/veerleprins/pen/RwoJjmK?editors=1100)
[Moon version 3](https://codepen.io/veerleprins/pen/BaQVJBJ?editors=1100)

#### What went right

After a lot of hassle and Sanne's theme session on gradients, I finally knew how it worked. This was what went well in the end: I practiced a lot without explanation and with explanation I just took that extra step to get my moon right. I am very proud of this:  
[Final version of my moon](https://codepen.io/veerleprins/pen/ZEBRvGN?editors=1100)

Furthermore, I started looking at different fonts to choose a font that fits the galaxy theme. Ultimately, I am quite proud of the Iceland font, which in my opinion fits best with the space theme. The disadvantage is that it took me quite a long time to find a nice font.

### Week 2

In this week we had a guest lectures and started with the first theme sessions to learn more about CSS. Since I was a bit lost at the moment and I didn't really know what I wanted anymore, I chose two theme sessions that seemed like fun to know more about. I chose the sessions: **Making Shapes** and **Animating**, both given by Sanne.

Due to personal circumstances, I found it difficult to stay motivated and come up with an idea of what I could make. This week I have been more concerned with the 'standard' styling. I spent hours thinking about what I could make and come up with a design that would get me a little more enthusiastic.

Eventually I came up with the idea to do something with 'space' and 'galaxy'. Based on the theme session _'animation'_ I decided to make animations that would match my galaxy theme.

That's how I started looking for small animations online. Eventually I came across a shooting star and started to recreate it. This was [Adam Wang's shooting star](https://codepen.io/adamp33/pen/FnlmG). But I wanted my animation to be something different: In Adam's shooting star the animation is extremely fast, namely only 1 second. I have adjusted my animation slightly using the animation-timing function.

#### What went wrong

What mainly went wrong is that it took me a long time before I had an idea that would make me enthusiastic. It also went wrong due to personal circumstances. Furthermore, making two animations on the title was not smooth either. I tried to add two animations on the same h1 element that would animate at the same time. This just didn't quite work. Below you can see a link in which that did not work completely:

[My codepen test with two animations](https://codepen.io/veerleprins/pen/gOLgPGE)
[My second codepen test with two animations](https://codepen.io/veerleprins/pen/NWbdMYK)

#### What went right

What went well was that I finally had an idea of where I wanted to work. The animations also went well. Through the theme session of this I finally understood how animations work and how to use them.

### Week 1

This week was the kick-off of the CSSttR course and it was told about the different assignments from which to choose. Since I've always had trouble with CSS myself and sometimes still don't quite understand the logic, it seemed wise not to go for the most difficult command, but the most obvious one. This was **Russ & Daughters' Menu**.

In this assignment it is the intention to make the styling for the menu card of Russ & Daughters. The HTML was supplied and it was intended as much as possible to leave this HTML as it was. However, parts can be added to the HTML which could be necessary for accessibility, for example.

#### Context

For this assignment it was the intention to choose a context that will be applied in the work. I chose to use the print-screen functionality option. If I still have time to spare, I am thinking about the prefers-color-scheme functionality.

#### Requirements

For this assignment it was also the intention to choose two requirements with which to work. I have chosen the following two requirements:

- Making the site responsive without media queries
- Using only two colors

#### Sketches

To get a bit of an idea of what I could make, I went to Pinterest to look at designs of Menu cards. Based on this inspiration, I thought it would be fun to create different pages in which the page can be turned. I also thought it would be nice to make a kind of folded folder that could be opened when the user wants to read it. I made two small sketches of this to get an idea of how the interaction would work:

<img width="824" alt="First sketch of my fist idea." src="https://user-images.githubusercontent.com/35265583/109821982-d0514f80-7c36-11eb-92c6-87883d699116.jpg">

<img width="824" alt="Second sketch of my first idea." src="https://user-images.githubusercontent.com/35265583/109821992-d2b3a980-7c36-11eb-958a-e6f30b1cae4d.jpg">

But I soon found myself unenthusiastic about this idea and worried that I wouldn't be able to do it. My **biggest challenges** are more with animations. I therefore decided to focus more on animations.

## :books: Sources

The sources I've used to create this webpage:

- Wang, A. (z.d.). Attention Required! | Cloudflare. Codepen. Geraadpleegd op 12 februari 2021, van https://codepen.io/adamp33/pen/FnlmG
- Verou, L. (z.d.). Contrast Ratio: Easily calculate color contrast ratios. Passing WCAG was never this easy! Contrast Ratio. Geraadpleegd op 12 februari 2021, van https://contrast-ratio.com/#%23c386f1-on-%23000344
- Divinector. (2020, 25 maart). Animated Background with Pure CSS and Html | No Javascript no Jquery [Video]. YouTube. https://www.youtube.com/watch?v=qx7pSLjLNQA&t=151s
- ’t Hooft, S. (z.d.). Attention Required! | Cloudflare. Codepen. Geraadpleegd op 11 februari 2021, van https://codepen.io/shooft/pen/dyOXrpZ
- MDN. (2021, 9 januari). clamp() - CSS: Cascading Style Sheets | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/CSS/clamp()
- MDN. (2021b, januari 19). brightness() - CSS: Cascading Style Sheets | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/brightness()
- Dodger. (2011, 19 november). CSS: background image on background color [StackOverflow post]. Stack Overflow. https://stackoverflow.com/questions/8195215/css-background-image-on-background-color
- freeCodeCamp.org. (2018, 16 september). Print Styles: CSS Tutorial (Day 6 of CSS3 in 30 Days) [Video]. YouTube. https://www.youtube.com/watch?v=CAgLAeykOyU&ab_channel=freeCodeCamp.org
- Online Tutorials. (2020, 30 december). Happy New Year Banner Animation | Twinkling Star Background Animation Effects using CSS & Javascript [Video]. YouTube. https://www.youtube.com/watch?v=Iw860SbfqP8&t=288s&ab_channel=OnlineTutorials
- Real Favicon Generator. (z.d.). Favicon Generator for perfect icons on all browsers. RealFaviconGenerator.net. Geraadpleegd op 3 maart 2021, van https://realfavicongenerator.net/
- MDN contributors. (2021, 31 januari). tabindex - HTML: HyperText Markup Language | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex
- Coyier, C. (2017, 11 juli). Basics of CSS Blend Modes. CSS-Tricks. https://css-tricks.com/basics-css-blend-modes/
- MDN. (2020, 18 december). - SVG: Scalable Vector Graphics | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/SVG/Element/feGaussianBlur
- MDN. (2021, 19 februari). - SVG: Scalable Vector Graphics | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/SVG/Element/feDropShadow
- MDN. (2021c, februari 19). drop-shadow() - CSS: Cascading Style Sheets | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow()
- MDN. (2021b, februari 19). - SVG: Scalable Vector Graphics | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/SVG/Element/feColorMatrix
- Envato Tuts+. (2019, 4 juli). Introduction to SVG Filters [Video]. YouTube. https://www.youtube.com/watch?v=bm6tkPzDObY&feature=emb_logo
- Cope, S. (2017, 27 februari). widows. CSS-Tricks. https://css-tricks.com/almanac/properties/w/widows/
- rnrneverdies. (2014, 18 november). Play multiple CSS animations at the same time [Stack Overflow Post]. Stack Overflow. https://stackoverflow.com/questions/26986129/play-multiple-css-animations-at-the-same-time
- Sanne, V. E. (z.d.). Materiaal bij themasessies - CSS to the Rescue 20/21. CSS to the Rescue 20/21. Geraadpleegd op 15 februari 2021, van https://cmda-minor-web.github.io/css-to-the-rescue-2021/themas.html
- MDN. (2021d, februari 19). hue-rotate() - CSS: Cascading Style Sheets | MDN. MDN Web Docs. https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/hue-rotate()

## :lock: License

This repo is licensed as [MIT]() by :copyright: [Veerle Prins](https://github.com/veerleprins), 2020
