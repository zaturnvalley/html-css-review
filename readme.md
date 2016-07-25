# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!-- 
<!DOCTYPE html>
<html>
<head>
  <title>My Page</title>
  <link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
<body>
<h1>My Page</>
<h3>About me</h3>
  <p>My name is Zach. Here are some things about me. </p>
<br>
  <p>I like</>
    <ul>
      <li>Food</li>
      <li>Sleep</li>
      <li>Swimming</li>
    </ul>

<script src="myscripts.js"></script>
</body>
</html>
 -->
```

2.) What are the differences between these tags?

```html
<!-- ^this goes at the top and bottom of your html
the img tag tells the source / path of your image and the alt is for if the img doesn't load, it'll display the text provided in place of the image  -->
<img src="images/me.jpg" alt="My profile image">

<!-- divs are like box sections that you can put things in / wrap around other html tags -->
<div></div>
```

```
Explain here.
```
--html goes at the top and bottom of your html

--the img tag tells the source / path of your image and the alt is for if the img doesn't load, it'll display the text provided in place of the image 

--divs are like box sections that you can put things in / wrap around other html tags

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* Below -- this will curve the border of the div into a circle */
div { 
  border-radius: 50%;
}

/* this will make the header class of the paragraph tag have an 18 pixel size font */
.header p {
  font-size: 18px;
}

/* This will make the footer class flat at the bottom of the page and position it absolutely / fixed */
.footer {
  position: absolute;
  bottom: 0;
}

/* This will make the splash image class have an ocean background image, will cover the existing area and full width */
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

/* This will give the ninja class a hover property that will change the font color to black when you hover over the element. It will override the display of the element and hide it as well. */
.ninja:hover {
  display: none;
  color: black;
}
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
