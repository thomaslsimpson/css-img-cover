CSS for filling a div with an image.

```
<div class='full-image ratio-wrapper-3-2' style='background-image: url(someimg.png);'>
	<div class='cover-color'>
		<p>Stuff</p>
	</div>
</div>
```

The `full-image` class specifier sets the background images (in the style) up properly to cover the DIV.

The 'cover-color' class uses predefined SASS variables:

- $cover-color-bg
- $cover-color-fg
- $cover-color-a

... to create a proper colored overlay. Use "rgba(...)" for a since colored overlay and gradients will 
be added in the next release.

