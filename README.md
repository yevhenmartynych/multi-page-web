<!-- # HTML Template Repository with HTML Proofer

This template repository includes preconfigured GitHub Action that will validate
html files in a project with
(HTMLProofer)[https://github.com/gjtorikian/html-proofer/]. And htmx to load
partials

```html
<main
  data-hx-trigger="load"
  data-hx-swap="outerHTML"
  data-hx-get="index.main.partial.html"
></main>
```

```js
function init() {
  import('...js');
}

const totalPartials = document.querySelectorAll(
  '[hx-trigger="load"], [data-hx-trigger="load"]'
).length;
let loadedPartialsCount = 0;

document.body.addEventListener('htmx:afterOnLoad', () => {
  loadedPartialsCount++;
  if (loadedPartialsCount === totalPartials) init();
});
```

Add the data-proofer-ignore attribute to any tag to ignore it from every check.

```html
<a href="https://notareallink" data-proofer-ignore>Not checked.</a>
``` -->

<br />
<div align="center">
  <a href="https://koldovsky.github.io/1329-team-02/">
    <img src="images/global/readme-logo.svg" alt="Logo" width="160">
  </a>

  <h3 align="center">EchoWave - Team Project</h3>

</div>

## 📌 Project Overview

The EchoWave website demonstrates our team's ability to design and develop a
static, visually appealing, and responsive web interface.<br>This project was
built collaboratively by our team using only <strong>HTML</strong>,
<strong>CSS</strong>, and <strong>JavaScript</strong>.

## 🔗 Project Link

Check out the live version of the project here: 
<a href="https://koldovsky.github.io/1329-team-02/" target="_blank"> 🖇️ EchoWave
Website</a>


### Tech Stack

[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=fff)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)

# Development team :

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yevhenmartynych)
  Yevhen Martynych **Team Lead**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ViktorSvertoka)
  Viktor Svertoka **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MarkiianSenkiv)
  Markiian Senkiv **Front End Developer**
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prohodec)
  Oleksandr Kopytin **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/micromoleckula)
  Dmytro Prokopenko **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yuliiashpylkatestqa)
  Yuliia Shpylka **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KravetsVA)
  Vladimir Kravets **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hola2005)
  Vladyslav Plakhotniuk **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Lytovchenkoo)
  Anhelina Lytovchenko **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rlnolino)
  Roman Lytvynenko **Front End Developer**

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/izkod)
  Izabella Kodzhebash **Front End Developer**
