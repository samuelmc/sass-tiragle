# sass-triangle
Add a triagle tip on a container's border

```
bower install --save sass-triangle
```

```
@import "bower_components/sass-triangle/triangle";
```

```
.triangle-tip-container {
  @include triangle-tip(
    $width: 20,
    $edge: top,
    $side: left,
    $offset: 15,
    $color: #000000,
    $fill: #ffffff,
    $thickness: 1,
    $rounded: 0
  );
}
```
