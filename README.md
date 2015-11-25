Simplr-Grid
---

Simple and Responsive CSS grid in less than 35 lines of SASS.

```sass
@import 'simplr-grid';

// createGrid(className, no. of columns, mobile-width);
@include createGrid('grid-6', 6);
```

This can be used as -

```html
<div class="grid-6">
    <div class="col-4"></div> <!-- 4th column of 6 column grid -->
    <div class="col-2"></div> <!-- 2/6 -->
</div>
```

Demo: http://samarjeet27.github.io/simplr-grid/
