---
title: MathBorderBox
type: docs
weight: 0
url: /php-java/mathborderbox/
---

# MathBorderBox class

 Draws a rectangular or some other border around the IMathElement. 
 
Example:
 
```php
  $borderBox = new MathBorderBox(new MathematicalText("x"));
```

## Constructors

| name | description |
| --- | --- |
| [MathBorderBox](/slides/php-java/mathborderbox/mathborderbox/)(IMathElement) | Creates MathBorderBox element with rectangular border |
| [MathBorderBox](/slides/php-java/mathborderbox/mathborderbox/)(IMathElement, boolean, boolean, boolean, boolean, boolean, boolean, boolean, boolean) | Creates MathBorderBox element |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBase](/slides/php-java/mathborderbox/getbase/)() | IMathElement | Base argument |
| [getChildren](/slides/php-java/mathborderbox/getchildren/)() | IMathElement | Get children elements |
| [getHideBottom](/slides/php-java/mathborderbox/gethidebottom/)() | boolean | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft](/slides/php-java/mathborderbox/gethideleft/)() | boolean | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight](/slides/php-java/mathborderbox/gethideright/)() | boolean | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [getHideTop](/slides/php-java/mathborderbox/gethidetop/)() | boolean | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [getStrikethroughBottomLeftToTopRight](/slides/php-java/mathborderbox/getstrikethroughbottomlefttotopright/)() | boolean | Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box. |
| [getStrikethroughHorizontal](/slides/php-java/mathborderbox/getstrikethroughhorizontal/)() | boolean | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughTopLeftToBottomRight](/slides/php-java/mathborderbox/getstrikethroughtoplefttobottomright/)() | boolean | Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box. |
| [getStrikethroughVertical](/slides/php-java/mathborderbox/getstrikethroughvertical/)() | boolean | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [setHideBottom](/slides/php-java/mathborderbox/sethidebottom/)(boolean) | void | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideLeft](/slides/php-java/mathborderbox/sethideleft/)(boolean) | void | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [setHideRight](/slides/php-java/mathborderbox/sethideright/)(boolean) | void | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [setHideTop](/slides/php-java/mathborderbox/sethidetop/)(boolean) | void | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [setStrikethroughBottomLeftToTopRight](/slides/php-java/mathborderbox/setstrikethroughbottomlefttotopright/)(boolean) | void | Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box. |
| [setStrikethroughHorizontal](/slides/php-java/mathborderbox/setstrikethroughhorizontal/)(boolean) | void | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughTopLeftToBottomRight](/slides/php-java/mathborderbox/setstrikethroughtoplefttobottomright/)(boolean) | void | Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box. |
| [setStrikethroughVertical](/slides/php-java/mathborderbox/setstrikethroughvertical/)(boolean) | void | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
