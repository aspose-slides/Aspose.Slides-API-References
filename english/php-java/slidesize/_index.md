---
title: SlideSize
type: docs
weight: 0
url: /php-java/slidesize/
---

# SlideSize class

 Represents a size of slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getOrientation](/slides/php-java/slidesize/getorientation/)() | int | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |
| [getSize](/slides/php-java/slidesize/getsize/)() | Dimension2D | Returns or sets the size in points. Read/write java.awt.geom.Dimension2D. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |
| [getType](/slides/php-java/slidesize/gettype/)() | int | Returns or sets the type of slide size. Read/write SlideSizeType. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |
| [setOrientation](/slides/php-java/slidesize/setorientation/)(int) | void | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |
| [setSize](/slides/php-java/slidesize/setsize/)(int, int) | void | Sets the type of slide size and scales content using scale type. |
| [setSize](/slides/php-java/slidesize/setsize/)(float, float, int) | void | Sets the size in points and scales content using scale type. |
