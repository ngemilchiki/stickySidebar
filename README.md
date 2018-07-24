# stickySidebar
Another simple sticky element

structure example
```html
<div class="parent">
  <div class="content">

  </div>
  <div class="sidebar">
    <div class="sticky">
    
    </div>
  </div>
</div>
```
```html
<script src="stickyElement.min.js"></script>
```
```javascript
var sticky = new stickyElement(".sticky",{
  minWidth : 600 // sticky sidebar works for minWidth 600px 
})
```
