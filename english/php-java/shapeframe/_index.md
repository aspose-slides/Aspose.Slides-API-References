---
title: ShapeFrame
type: docs
weight: 0
url: /php-java/shapeframe/
---

# ShapeFrame class

 Represents shape frame's properties.
 

## Constructors

| name | description |
| --- | --- |
| [ShapeFrame](/slides/php-java/shapeframe/shapeframe/)(float, float, float, float, byte, byte, float) | Creates new shape frame's properties. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [cloneT](/slides/php-java/shapeframe/clonet/)() | IShapeFrame | Clones. |
| [deepClone](/slides/php-java/shapeframe/deepclone/)() | Object | Clones |
| [equals](/slides/php-java/shapeframe/equals/)(Object) | boolean | Returns a value indicating whether this instance is equal to a specified object. |
| [equals](/slides/php-java/shapeframe/equals/)(ShapeFrame) | boolean | Returns a value indicating whether this instance is equal to a specified object. |
| [getCenterX](/slides/php-java/shapeframe/getcenterx/)() | float | Returns the X coordinate of a frame's center. Read-only float. |
| [getCenterY](/slides/php-java/shapeframe/getcentery/)() | float | Returns the Y coordinate of a frame's center. Read-only float. |
| [getFlipH](/slides/php-java/shapeframe/getfliph/)() | byte | Determines whether a frame is flipped horizontally. Read-only NullableBool. |
| [getFlipV](/slides/php-java/shapeframe/getflipv/)() | byte | Determines whether a frame is flipped vertically. Read-only NullableBool. |
| [getHeight](/slides/php-java/shapeframe/getheight/)() | float | Returns the height of a frame. Read-only float. |
| [getRectangle](/slides/php-java/shapeframe/getrectangle/)() | Float | Returns the coordinates of a frame. Read-only java.awt.geom.Rectangle2D.Float. |
| [getRotation](/slides/php-java/shapeframe/getrotation/)() | float | Returns the number of degrees a frame is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read-only float. |
| [getWidth](/slides/php-java/shapeframe/getwidth/)() | float | Returns the width of a frame. Read-only float. |
| [getX](/slides/php-java/shapeframe/getx/)() | float | Returns the X coordinate of the upper-left corner of a frame. Read-only float. |
| [getY](/slides/php-java/shapeframe/gety/)() | float | Returns the Y coordinate of the upper-left corner of a frame. Read-only float. |
