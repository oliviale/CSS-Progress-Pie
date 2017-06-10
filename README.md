# CSS Progress Pie
===
This is a progress pie done in CSS. It came about when I needed a simple progress pie but didn't want to rely on any JS plugins as they took too long to load for a specific situation at work. I also felt that my CTO was going to strangle me if I introduce another JS plugin, especially one just for aethestic purposes :sweat_smile:.

## Examples
---

![CSS Progress Pie examples](http://url/to/img.png)

[See here for examples](images/example.png)

## How To Use
---
1. Download the CSS/SCSS file and include it in your `<head>`. There are two kinds - default (single color) or multi-colored with red, yellow and green for the numbers 1-40, 41-70 and 71-100 respectively.
``` html
<div class="progress-pie" data-value="50"></div>
```
2. HTML structure
``` html
<div class="progress-pie" data-value="50"></div>
```
3. Uh... that's it.

## Changing colors, fonts, etc.
---
Manually change the properties of the CSS code. Your life will be easier if you use the SCSS file instead of the pure CSS file as you would need to alter for every `data-value`.

##Playground
---
[Play around in this Codepen](https://codepen.io/oliviale/pen/YqEgPw)

##License and other stuff
---
Do whatever you want license, but preferably do not delete the author comments in the CSS file :joy:.
Also, if you do end up using this and do wonderful things like you wonderful people always do, forking or tweeting your work at [me](http://twitter.com/meowlivia_) is appreciated.
