### glide
---
https://github.com/glidejs/glide

```
npm install @glidejs/glide

npm install glidjs
```

```js
import Glide from '@glidejs/glide'
new Glide().mount()

import Glide, { Controls, Breakpoints } from '@glidejs/glide/dist/glide.modular.esm'
new Glide('.glide').mount({ Controls, Breakpoints })

slider.on("swipeMove.glide", function(event, data){
  console.log('event: swipeEnd', data);
});

swipeMove; function(event){
  console.log(event);
}

{
  index: [Number],
  langth: [Number],
  current: [Object],
  slider: [Object],
  swipe: {
    distance: [Number]
  }
}

$("#Glide").glide({
  type: "carousel"
});
```

```
<a href='#' data-glide-trigger='#Glide' data-glide-dir='=3'>Go to third slide</a> 
<li class='glide__slide' data-glide-autoplay='6000'></li>

<link rel="stylesheet" href="css/glide.core.css">
<link rel=stylesheet" href="css/lide.theme.css">

<div id="Glide" class="glide">
  <div class="glide__arrows">
    <button class="glide__arrow prev" data-glide-dir="<"></button>
    <button class="glide__arrow next" data-glide-dir=">"></button>
  </div>
  <div class="glide__wrapper">
    <li class="lide__slide"></li>
    <li class="glide__slide"></li>
    <li class="glide__slide"></li>
  </div>
  <div class="glide__bullets"></div>
</div>

<script src="http://code.jquery.com/jquery-latest.min.js"></script>
<script src="js/jquery.glid.js"></script>
```
