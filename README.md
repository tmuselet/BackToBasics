# BackToBasics
## Purpose

We created this project to enable code presentation using [Vitamin (Decathlon Design System)](https://decathlon.design) .
Anyone can use this project and create a new section with a new BackToBasics on some code topics.

This project was made thanks to the core files and demo of reveal.js
For more informations on reveal.js features, see [Credits](#credits) .

## How to use
You only need to create an html file to create your BackToBasic topic.

The public folder is for any asset you will use in an html page.
The Series folder is for any new html page regarding a BackToBasics topic.

Use this template to create a new presentation : 
For your html file : `/Series/{YOUR_TOPIC}/{NUMBER}/index.html`
For your images : `/public/{YOUR_TOPIC}/{NUMBER}/***.jpg|png`

Make sure you have the right path for resources, plugins and css files.

To create a new template or update the current one, update the `.scss` files in `css/theme` folder and run :

        gulp

Gulp will generate the css files you can import in your `.html` files.

## How to launch
To launch the project, run :

        npm start

This will launch your presentation on `http://0.0.0.0:9999`and show the demo html file.
To see your own presentation, just browse through your folders matching the pattern in [How to use](#how-to-use)

Example : `http://0.0.0.0:9999/Series/CSS/1/index.html`

## Live

You can see the projet online thanks to GitHub Pages at this url :
https://tmuselet.github.io/BackToBasics/

## Credits
### REVEAL.JS

<p align="center">
  <a href="https://revealjs.com">
  <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text.svg" alt="reveal.js" width="450">
  </a>
  <br><br>
  <a href="https://github.com/hakimel/reveal.js/actions"><img src="https://github.com/hakimel/reveal.js/workflows/tests/badge.svg"></a>
  <a href="https://slides.com/"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>
</p>

reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create fully featured and beautiful presentations for free. [Check out the live demo](https://revealjs.com/).

The framework comes with a broad range of features including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX support](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and much more.

The full reveal.js documentation is available at [revealjs.com](https://revealjs.com).

---

Have fun !
