# Bulma Cheatsheet

รวมสูตรโกงสำหรับการใช้งาน Bulma

## 👍 เว็บไซต์รวบรวมการใช้ Bulma CSS เพิ่มเติม

- [หน้าเว็บหลัก](https://bulma.io/)
- [ธีมสำหรับการใช้งาน](https://bulmatemplates.github.io/bulma-templates/)
- [ตัวอย่างผลลัพธ์สำหรับการใช้งาน Bulma](https://bulma.io/expo/)
- [ส่วนเสริม Components สำหรับ Bulma](https://bulma.io/extensions/)
- [การใช้ร่วมกับ Vue.js (Buefy)](https://buefy.org/)
- [Fontawesome สำหรับใช้ไอคอนบนเว็บ Bulma](https://fontawesome.com/)

## ⤵️ การนำไปใช้งานผ่าน cdnjs

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.9.2/css/bulma.min.css">
```

## ⤵️ การนำไปใช้งานผ่าน npm

```bash
npm install bulma
```

## 📱💻🖥️ Breakpoints (ขนาดตามอุปกรณ์)

|ชื่อ Class|ขนาดเริ่มต้น|ขนาดสูงสุด|
|-|-|-|
|mobile|-|`768px`|
|tablet|`769px`|`1023px`|
|desktop|`1024px`|`1215px`|
|widescreen|`1216px`|`1407px`|
|fullhd|`1408px`|-|

## 🏗️ การทำให้ HTML ใช้งานตามสไตล์ปกติ

```html
<div class="content">
  <h1>Heading</h1>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
</div>
```

## 🎨 สีข้อความ

|ชื่อ Class|ตัวอย่าง|
|-|-|
|`.has-text-white`|<span class="has-text-white">Hello, world!</span>|
|`.has-text-light`|<span class="has-text-light">Hello, world!</span>|
|`.has-text-grey`|<span class="has-text-grey">Hello, world!</span>|
|`.has-text-dark`|<span class="has-text-dark">Hello, world!</span>|
|`.has-text-black`|<span class="has-text-black">Hello, world!</span>|
|`.has-text-primary`|<span class="has-text-primary">Hello, world!</span>|
|`.has-text-link`|<span class="has-text-link">Hello, world!</span>|
|`.has-text-info`|<span class="has-text-info">Hello, world!</span>|
|`.has-text-success`|<span class="has-text-success">Hello, world!</span>|
|`.has-text-warning`|<span class="has-text-warning">Hello, world!</span>|
|`.has-text-danger`|<span class="has-text-danger">Hello, world!</span>|

## 🎨 สีพื้นหลัง

|ชื่อ Class|ตัวอย่าง|
|-|-|
|`.has-background-white`|<span class="has-background-white">Hello, world!</span>|
|`.has-background-light`|<span class="has-background-light">Hello, world!</span>|
|`.has-background-grey`|<span class="has-background-grey">Hello, world!</span>|
|`.has-background-dark`|<span class="has-background-dark">Hello, world!</span>|
|`.has-background-black`|<span class="has-background-black">Hello, world!</span>|
|`.has-background-primary`|<span class="has-background-primary">Hello, world!</span>|
|`.has-background-link`|<span class="has-background-link">Hello, world!</span>|
|`.has-background-info`|<span class="has-background-info">Hello, world!</span>|
|`.has-background-success`|<span class="has-background-success">Hello, world!</span>|
|`.has-background-warning`|<span class="has-background-warning">Hello, world!</span>|
|`.has-background-danger`|<span class="has-background-danger">Hello, world!</span>|

## 📐 กำหนดระยะห่าง (Margin)

> ได้มุมล่ะ `0` ถึง `6`

|ชื่อ Class|ย่อ|ผลลัพธ์|
|-|-|-|
|`.m-5`|All|ห่างทุกมุม 5 หน่วย|
|`.mt-5`|Top|ห่างมุมบน 5 หน่วย|
|`.mb-5`|Bottom|ห่างมุมล่าง 5 หน่วย|
|`.ml-5`|Left|ห่างมุมซ้าย 5 หน่วย|
|`.mr-5`|Right|ห่างมุมขวา 5 หน่วย|
|`.mx-5`|X-Axis|ห่างมุมซ้ายขวา 5 หน่วย|
|`.my-5`|Y-Axis|ห่างมุมบนล่าง 5 หน่วย|

## 📐 กำหนดขยายขอบ (Padding)

> ได้มุมล่ะ `0` ถึง `6`

|ชื่อ Class|ย่อ|ผลลัพธ์|
|-|-|-|
|`.p-5`|All|ห่างทุกมุม 5 หน่วย|
|`.pt-5`|Top|ห่างมุมบน 5 หน่วย|
|`.pb-5`|Bottom|ห่างมุมล่าง 5 หน่วย|
|`.pl-5`|Left|ห่างมุมซ้าย 5 หน่วย|
|`.pr-5`|Right|ห่างมุมขวา 5 หน่วย|
|`.px-5`|X-Axis|ห่างมุมซ้ายขวา 5 หน่วย|
|`.py-5`|Y-Axis|ห่างมุมบนล่าง 5 หน่วย|

## 🔤 กำหนดขนาดข้อความ

|ชื่อ Class|ขนาด|ผลลัพธ์|
|-|-|-|
|`.is-size-1`|`3rem`|<span class="is-size-1">Hello</span>|
|`.is-size-2`|`2.5rem`|<span class="is-size-2">Hello</span>|
|`.is-size-3`|`2rem`|<span class="is-size-3">Hello</span>|
|`.is-size-4`|`1.5rem`|<span class="is-size-4">Hello</span>|
|`.is-size-5`|`1.25rem`|<span class="is-size-5">Hello</span>|
|`.is-size-6`|`1rem`|<span class="is-size-6">Hello</span>|
|`.is-size-7`|`0.75rem`|<span class="is-size-7">Hello</span>|

## 🔤 การจัดตำแหน่งข้อความ

|ชื่อ Class|ผลลัพธ์|
|-|-|
|`.has-text-centered`|<div class="has-text-centered">Hello My World</div>
|`.has-text-left`|<div class="has-text-left">Hello My World</div>
|`.has-text-right`|<div class="has-text-right">Hello My World</div>

## 🔤 การจัดรูปแบบข้อความ

|ชื่อ Class|ผลลัพธ์|
|-|-|
|`.is-capitalized`|Hello World|
|`.is-lowercase`|hello world|
|`.is-uppercase`|HELLO WORLD|

## 🔤 กำหนดหัวข้อและคำอธิบาย

> `is-*` มีขนาด `1` ถึง `6` หรือไม่ใช้ก็ได้

```html
<h2 class="title is-2">Title</h2>
<h3 class="subtitle is-4">Subtitle</h3>
```

## 📺 การกำหนด Display

|ชื่อ Class|ความหมาย|
|-|-|
|`.is-block`|Block|
|`.is-flex`|Flexbox|
|`.is-inline`|Inline|
|`.is-inline-block`|Inline Block|
|`.is-inline-flex`|Inline Flex|

## 📺 การซ่อนเนื้อหา

|ชื่อ Class|ผลลัพธ์|
|-|-|
|`.is-hidden`|ซ่อนทั้งหมด|
|`.is-hidden-touch`|ซ่อนเฉพาะขนาด mobile, tablet|
|`.is-hidden-tablet`|ซ่อนเฉพาะขนาด tablet, desktop, widescreen, fullhd|
|`.is-hidden-desktop`|ซ่อนเฉพาะขนาด desktop, widescreen, fullhd|
|`.is-hidden-widescreen`|ซ่อนเฉพาะขนาด widescreen, fullhd|
|`.is-hidden-fullhd`|ซ่อนเฉพาะขนาด fullhd|

## 💪 การใช้ Flex อย่างรวดเร็ว

> ใช้ `*` ตาม Value ที่ต้องการ

- `.is-flex-direction-*`
- `.is-flex-wrap-*`
- `.is-justify-content-*`
- `.is-align-content-*`
- `.is-align-items-*`
- `.is-align-self-*`
- `.is-flex-grow-*`
- `.is-flex-shrink-*`

## 🧰 Class ช่วยเหลืออื่นๆ

|ชื่อ Class|ผลลัพธ์|
|-|-|
|`.is-pulled-left`|`float: left;`|
|`.is-pulled-right`|`float: right;`|
|`.is-clipped`|`overflow: hidden;`|
|`.is-radiusless`|`border-radius: 0;`|
|`.is-shadowless`|`box-shadow: none;`|
|`.is-unselectable`|`pointer-events: none;`|
|`.is-clickable`|`cursor: pointer;`|
|`.is-relative`|`position: relative;`|

## 🔲 Container + Section

```html
<section class="section">
  <div class="container">
    <!-- body -->
  </div>
</section>
```

## 🔲 Block (สร้างระยะห่างระหว่างเนื้อหา)

```html
<nav class="block"></nav>
<main class="block"></main>
<footer class="block"></footer>
```

## 🍱 Columns

> ใช้กำหนดขนาด `is-*` ตามจำนวนที่ต้องการ ให้ครบ `12` หน่วย

```html
<div class="columns">
  <div class="column is-2"></div>
  <div class="column is-8"></div>
  <div class="column is-2"></div>
</div>
```

## 🍱 Column Option

```html
<div class="columns">
  <div class="column is-narrow"></div>
  <div class="column is-offset-2"></div>
  <div class="column is-2-desktop"></div>
</div>
```

|ชื่อ Class|ความหมาย|
|-|-|
|`.is-narrow`|ปรับขนาดคอลัมน์ตามเนื้อหา|
|`.is-offset-*`|ปรับระยะห่างทางซ้ายตามหน่วย|
|`.is-*-desktop`|ปรับขนาดเฉพาะหน้าจอ Desktop เท่านั้น และขนาดอื่นๆ|

## 🍱 Columns Options

```html
<div class="columns is-centered is-multiline">
  <!--  -->
</div>
```

|ชื่อ Class|ความหมาย|
|-|-|
|`.is-mobile`|บังคับขนาดคอลัมน์บนมือถือ|
|`.is-multiline`|รองรับคอลัมน์แบบหลายบรรทัด|
|`.is-gapless`|นำ Margin ของแต่ล่ะคอลัมน์ออก|
|`.is-centered`|ปรับกึ่งกลางในแนวนอน|
|`.is-vcentered`|ปรับกึ่งกลางในแนวตั้ง|

## 🍡 Level

> การแสดงผลของ Level เหมือนกับ Flexbox

```html
<!-- แบ่งซ้าย-ขวา -->
<div class="level">
  <div class="level-left"></div>
  <div class="level-right"></div>
</div>

<!-- เนื้อหากึ่งกลาง -->
<div class="level">
  <div class="level-item"></div>
  <div class="level-item"></div>
  <div class="level-item"></div>
</div>

<!-- บังคับให้มือถือแสดงตามตำแหน่ง -->
<div class="level is-mobile">
  <div class="level-item"></div>
  <div class="level-item"></div>
  <div class="level-item"></div>
</div>
```

## 🧭 Navbar

> - สำหรับการกำหนดสี
>   - `.is-dark`
>   - `.is-light`
>   - `.is-primary`
>   - `.is-link`
>   - `.is-info`
>   - `.is-success`
>   - `.is-warning`
>   - `.is-danger`
> - กำหนดเงาด้วย `.has-shadow`
> - กำหนดขยายขนาด `.is-spaced`

```html
<nav class="navbar is-dark has-shadow is-spaced">
  <div class="navbar-brand">
    <!-- แสดงตลอดเวลา -->
  </div>

  <div class="navbar-menu">
    <!-- ซ่อนก็ต่อเมื่อขนาดมือถือ -->
    <div class="navbar-start">
      <!-- แสดงฝั่งซ้าย -->
    </div>
    <div class="navbar-end">
      <!-- แสดงฝั่งขวา -->
    </div>
  </div>

  <div class="navbar-item">
    <!-- แสดงรายการ ได้ทั้งภายใน .navbar, .navbar-brand, .navbar-start, .navbar-end -->
  </div>
</nav>
```

## 🧭 JavaScript สำหรับการเปิด narbar-menu

```html
<nav class="navbar">
  <div class="navbar-brand">
    <a role="button" class="navbar-burger" data-target="navMenu" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div class="navbar-menu" id="navMenu">
    <div class="navbar-start">
      <a href="#" class="navbar-item">Link 1</div>
      <a href="#" class="navbar-item">Link 2</div>
    </div>
  </div>
</nav>
```

```js
document.addEventListener('DOMContentLoaded', () => {
  const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0)
  if ($navbarBurgers.length > 0) {
    $navbarBurgers.forEach( el => {
      el.addEventListener('click', () => {
        const target = el.dataset.target
        const $target = document.getElementById(target)
        el.classList.toggle('is-active')
        $target.classList.toggle('is-active')
      })
    })
  }
})
```

## 🧭 Navbar Dropdown

```html
<nav class="navbar" role="navigation" aria-label="dropdown navigation">
  <div class="navbar-item has-dropdown is-hoverable">
    <a class="navbar-link">
      Docs
    </a>
    <div class="navbar-dropdown">
      <a class="navbar-item">
        Overview
      </a>
      <a class="navbar-item">
        Elements
      </a>
      <a class="navbar-item">
        Components
      </a>
      <hr class="navbar-divider">
      <div class="navbar-item">
        Version 0.9.2
      </div>
    </div>
  </div>
</nav>
```

## 🦸‍♂️ Hero

> - สำหรับการกำหนดสี
>   - `.is-dark`
>   - `.is-light`
>   - `.is-primary`
>   - `.is-link`
>   - `.is-info`
>   - `.is-success`
>   - `.is-warning`
>   - `.is-danger`
> - สำหรับการกำหนดขนาด
>   - `.is-small`
>   - `.is-medium`
>   - `.is-large`
>   - `.is-halfheight`
>   - `.is-fullheight`

```html
<section class="hero is-success is-fullheight">

  <header class="hero-head">
    <!-- header -->
  </header>

  <main class="hero-body">
    <!-- main -->
  </main>

  <footer class="hero-foot">
    <!-- footer -->
  </footer>

</section>
```

## 🗣️ Media Object

```html
<article class="media">
  <div class="media-left">
    <!-- avatar -->
  </div>

  <div class="media-content">
    <!-- text -->
  </div>

  <div class="media-left">
    <!-- actions -->
  </div>
</article>
```

## 👣 Footer

```html
<footer class="footer">
  <div class="content has-text-centered">
    Copyright 2021
  </div>
</footer>
```

## 📦 Box

```html
<div class="box">
  <!--  -->
</div>
```

## 🃏 Card

```html
<div class="card">
  <div class="card-header">
    <h2 class="card-header-title">Title</h2>
    <div class="card-header-icon">
      <span class="icon">
        <i class="fas fa-angle-down"></i>
      </span>
    </div>
  </div>

  <div class="card-image">
    <!-- image -->
  </div>

  <div class="card-content">
    <!-- body -->
  </div>

  <div class="card-footer">
    <a href="#" class="card-footer-item">Save</a>
    <a href="#" class="card-footer-item">Edit</a>
    <a href="#" class="card-footer-item">Delete</a>
  </div>
</div>
```

## 🆗 Button

> - `is-*` ตามด้วยโค้ดสีปรับสีได้ เช่น `is-link`
> - `is-*` ตามด้วยขนาด เช่น `is-large`
> - `is-light` ปรับรูปแบบเป็นสีบาง
> - `is-outlined` ปรับรูปแบบเป็นขอบสี
> - `is-rounded` ปรับรูปแบบเป็นขอบกลม
> - `is-fullwidth` ปรับขนาดเป็นเต็ม Block
> - `is-loading` แสดงการโหลด

```html
<a href="#" class="button">Link</a>
<button class="button is-link">Submit</button>
<button class="button is-link is-light">Light</button>
<button class="button is-link is-outlined">Outlined</button>
<button class="button is-link is-fullwidth">Fullwidth</button>
<button class="button is-link is-loading">Loading</button>
```

## 🆗 Button Group

> - `is-centered` ปรับปุ่มให้อยู่กึ่งกลาง
> - `is-right` ปรับปุ่มให้อยู่ชิดขวา
> - `has-addons`

```html
<div class="buttons is-centered has-addons">
  <a href="#" class="button">Link 1</a>
  <a href="#" class="button">Link 2</a>
  <a href="#" class="button">Link 3</a>
</div>
```

## ❌ Delete (ปุ่มกากาบาท)

```html
<button class="delete is-small"></button>
```

## 🎈 Container สำหรับ Icon

```html
<span class="icon">
  <i class="fas fa-home"></i>
</span>
```

```html
<span class="icon-text">
  <span class="icon">
    <i class="fas fa-home"></i>
  </span>
  <span>Home</span>
</span>
```

## 🖼️ Container สำหรับ Image

> ขนาดมี `16x16` `24x24` `32x32` `48x48` `64x64` `96x96` `128x128`

```html
<figure class="image is-128x128">
  <img class="is-rounded" src="https://bulma.io/images/placeholders/128x128.png">
</figure>
```

## 🎞️ Container สำหรับวิดีโอ และยืดหยุ่นตามขนาด
****
```html
<figure class="image is-16by9">
  <iframe class="has-ratio" width="640" height="360" src="https://www.youtube.com/embed/YE7VzlLtp-4" frameborder="0" allowfullscreen></iframe>
</figure>
```

## 📣 Notification

```html
<div class="notification is-info is-light">
  <button class="delete"></button>
  <p>Message</p>
</div>
```

## 💬 Message

```html
<article class="message is-info">
  <div class="message-header">
    <h3>Title</h3>
    <button class="delete"></button>
  </div>
  <div class="message-body">
    <p>Message</p>
  </div>
</article>
```

```html
<article class="message is-info">
  <div class="message-body">
    <p>Message</p>
  </div>
</article>
```

## 📈 Progress

```html
<progress class="progress is-small is-link" max="100"></progress>
```

## 📊 Table

```html
<div class="table-container">
  <table class="table is-striped is-narrow is-hoverable">
    <thead>
      <tr>
        <th>One</th>
        <th>Two</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>หนึ่ง</td>
        <td>สอง</td>
      </tr>
      <tr>
        <td>一</td>
        <td>二</td>
      </tr>
    </tbody>
  </table>
</div>
```

|ชื่อ Class เสริม|ความหมาย|
|-|-|
|`.is-bordered`|เพิ่มขอบตาราง|
|`.is-striped`|เพิ่มสีตัดของแถวคู่|
|`.is-narrow`|ทำให้ตารางมีขนาดเล็ก|
|`.is-hoverable`|ทำให้ตารางแสดงสีเมื่อชี้แถว|
|`.is-fullwidth`|ทำให้ตารางเต็มขอบ|

## 🏷️ Tags

```html
<span class="tag is-success is-light">Success</span>
<span class="tag is-success is-light is-large">Large</span>
<span class="tag is-success is-light is-rounded">Rounded</span>
<span class="tag is-success is-light is-delete"></span>
```

```html
<div class="tags are-large">
  <span class="tag">All</span>
  <span class="tag">Large</span>
  <span class="tag">Size</span>
</div>
```

```html
<div class="tags has-addons">
  <span class="tag is-dark">version</span>
  <span class="tag is-info">1.0.0</span>
</div>
```

## 🍞 Breadcrumb

```html
<nav class="breadcrumb">
  <ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
    <li class="is-active"><a href="#">Link Active</a></li>
  </ul>
</nav>
```

## 🔽 Dropdown

> เปลี่ยนจาก `.is-active` เป็น `.is-hoverable` เพื่อให้ชี้สำหรับเปิด Dropdown แทน

```html
<div class="dropdown is-active">
  <div class="dropdown-trigger">
    <button class="button">
      <span>Dropdown</span>
    </button>
  </div>

  <div class="dropdown-menu">
    <div class="dropdown-content">
      <a href="#" class="dropdown-item">Item 1</a>
      <a href="#" class="dropdown-item">Item 2</a>
      <hr class="dropdown-divider">
      <a href="#" class="dropdown-item">Item 3</a>
    </div>
  </div>
</div>
```

## 🍽️ Menu

```html
<aside class="menu">
  <p class="menu-label">Item 1</p>
  <ul class="menu-list">
    <li><a href="#">Item 1.1</a></li>
    <li><a href="#">Item 1.2</a></li>
  </ul>

  <p class="menu-label">Item 2</p>
  <ul class="menu-list">
    <li><a href="#">Item 2.1</a></li>
    <li>
      <a href="#" class="is-active">Item 2.2</a>
      <ul>
        <li><a href="#">Item 2.2.1</a></li>
        <li><a href="#">Item 2.2.2</a></li>
      </ul>
    </li>
  </ul>
</aside>
```

## 📟 Modal

> ให้เติม `.modal.is-active` ผ่าน JavaScript ด้วยตนเอง เพื่อแสดงผล Modal

```html
<div class="modal">
  <div class="modal-background"></div>
  <div class="modal-content">
    <!-- body -->
  </div>
  <button class="modal-close is-large"></button>
</div>
```

```html
<div class="modal">
  <div class="modal-background"></div>
  <div class="modal-card">
    <header class="modal-card-head">
      <p class="modal-card-title">Title</p>
      <button class="delete"></button>
    </header>
    <section class="modal-card-body">
      <!-- body -->
    </section>
    <footer class="modal-card-foot">
      <button class="button is-success">Save</button>
      <button class="button">Cancel</button>
    </footer>
  </div>
</div>
```

## 📃 Pagination

```html
<nav class="pagination is-centered is-rounded">
  <a class="pagination-previous">ก่อนหน้า</a>
  <a class="pagination-next">ถัดไป</a>

  <ul class="pagination-list">
    <li><a class="pagination-link">1</a></li>

    <li><span class="pagination-ellipsis">&hellip;</span></li>

    <li><a class="pagination-link">45</a></li>
    <li><a class="pagination-link is-current">46</a></li>
    <li><a class="pagination-link">47</a></li>

    <li><span class="pagination-ellipsis">&hellip;</span></li>

    <li><a class="pagination-link">86</a></li>
  </ul>
</nav>
```

## 🎛️ Panel

```html
<article class="panel is-success">
  <p class="panel-heading">Title</p>

  <p class="panel-tabs">
    <a href="#" class="is-active">Tab 1</a>
    <a href="#">Tab 2</a>
    <a href="#">Tab 3</a>
    <a href="#">Tab 4</a>
  </p>

  <div class="panel-block">
    <p class="control">
      <input class="input" type="text" placeholder="Search">
    </p>
  </div>

  <a href="#" class="panel-block is-active has-text-success">Item 1</a>
  <a href="#" class="panel-block is-active">Item 2</a>
  <a href="#" class="panel-block is-active">Item 3</a>
  <a href="#" class="panel-block is-active">Item 4</a>
</article>
```

## 📑 Tabs

> รูปแบบที่มี ได้แก่ `.tabs.is-boxed` `.tabs.is-toggle` `.tabs.is-toggle.is-toggle-rounded` `.tabs.is-fullwidth`

```html
<div class="tabs is-centered">
  <ul>
    <li class="is-active"><a href="#">Tab 1</a></li>
    <li><a href="#">Tab 2</a></li>
    <li><a href="#">Tab 3</a></li>
    <li><a href="#">Tab 4</a></li>
  </ul>
</div>
```

## 📄 Form

```html
<form action="/" method="POST">
  <div class="field">
    <label class="label">Title:</label>
    <div class="control">
      <input class="input" type="text" placeholder="Your title here." required>
    </div>
    <p class="help is-info">Title must be includes</p>
  </div>

  <div class="field">
    <label class="label">Message:</label>
    <div class="control">
      <textarea class="textarea" placeholder="Your message."></textarea>
    </div>
  </div>

  <div class="field">
    <div class="control">
      <div class="buttons">
        <button class="is-link">Submit</button>
        <button class="is-link is-light">Cancel</button>
      </div>
    </div>
  </div>
</form>
```

## 📄 Form ในแนวนอน

```html
<form action="/" method="POST">
  <div class="field is-horizontal">
    <div class="field-label is-normal">
      <label class="label">From</label>
    </div>

    <div class="field-body">
      <div class="field">
        <p class="control is-expanded">
          <input class="input" type="text" placeholder="First name">
          <span class="icon is-small is-left">
            <i class="fas fa-user"></i>
          </span>
        </p>
      </div>

      <div class="field">
        <p class="control is-expanded">
          <input class="input" type="text" placeholder="Last name">
        </p>
      </div>
    </div>
  </div>
</form>
```

## ⌨️ Input พร้อม Icon

```html
<div class="field">
  <div class="control has-icons-left has-icons-right">
    <input class="input" type="email" placeholder="Email">

    <span class="icon is-small is-left">
      <i class="fas fa-envelope"></i>
    </span>

    <span class="icon is-small is-right">
      <i class="fas fa-check"></i>
    </span>
  </div>
</div>
```

## ⌨️ Input พร้อมปุ่ม

> ใช้ `.control.is-expanded` เพื่อขยายขนาดช่วงควบคุมเนื้อหาให้เต็ม Block

```html
<div class="field has-addons">
  <div class="control">
    <input class="input" type="text" placeholder="Keyword...">
  </div>

  <div class="control">
    <a class="button is-link">
      Search
    </a>
  </div>
</div>
```

```html
<div class="field has-addons">
  <div class="control">
    <input class="input" type="text" placeholder="Your email">
  </div>

  <div class="control">
    <a class="button is-static">@gmail.com</a>
  </div>
</div>
```

## ⌨️ Input พร้อมสีขอบสถานะ

```html
<div class="control">
  <input type="text" class="input is-success" placeholder="Ok!">
</div>

<div class="control">
  <input type="text" class="input is-danger" placeholder="Not ok!">
</div>
```

## ⌨️ Input พร้อมสถานะการโหลด

```html
<div class="control">
  <input type="text" class="input is-loading" placeholder="Loading...">
</div>
```

## ⌨️ Textarea

```html
<div class="control">
  <textarea class="textarea is-loading is-warning">Loading...</textarea>
</div>
```

## 👉 Select

```html
<div class="control">
  <div class="select">
    <select>
      <option>None</option>
      <option>Male</option>
      <option>Female</option>
    </select>
  </div>
</div>
```

```html
<div class="control">
  <div class="select is-multiple">
    <select multiple>
      <option>กรุงเทพฯ</option>
      <option>นนทบุรี</option>
      <option>ปทุมธานี</option>
      <option>สมุทรปราการ</option>
      <option>นครปฐม</option>
    </select>
  </div>
</div>
```

## ☑️ Checkbox

```html
<div class="control">
  <label class="checkbox">
    <input type="checkbox">
    Remember me
  </label>
</div>
```

## 🔘 Radio

```html
<div class="control">
  <label class="radio">
    <input type="radio" name="answer">
    Yes
  </label>
  <label class="radio">
    <input type="radio" name="answer">
    No
  </label>
</div>
```

## 📂 File

> ใช้ Class `.file.has-name.is-boxed` เพื่อปรับเป็นแบบกล่องแทน และต้องใช้ JavaScript เพิ่มเติมสำหรับการกำหนดชื่อไฟล์ที่ได้เลือก

```html
<div class="file">
  <label class="file-label">
    <input class="file-input" type="file" name="resume">

    <span class="file-cta">
      <span class="file-icon">
        <i class="fas fa-upload"></i>
      </span>
      <span class="file-label">
        Choose a file…
      </span>
    </span>

    <span class="file-name">
      Filename.extension
    </span>
  </label>
</div>
```
