# Spirograph Desk

Roll a little circle inside a bigger one and let a moving pen trace its path.

## Run

https://raeeskasim1.github.io/spirograph-desk/

## Try it

Sweep the inner radius and pen offset. Try d = 0, then choose coprime radii and compare the closing period.

## How it works

The curve is a hypotrochoid, calculated directly from the displayed parametric equations. Integer radii let the greatest common divisor determine a full closing period. The canvas scales to the curve extent; a second slightly offset line adds a decorative layer.
