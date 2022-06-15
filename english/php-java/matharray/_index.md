---
title: MathArray
type: docs
weight: 0
url: /php-java/matharray/
---

# MathArray class

 Specifies a vertical array of equations or any mathematical objects 
 
Example:
 
```php
  $mathArray = new MathArray(new MathematicalText("item1"));
```

## Constructors

| name | description |
| --- | --- |
| [MathArray](/slides/php-java/matharray/matharray/)(IMathElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](/slides/php-java/matharray/matharray/)(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) | Creates a mathematical array and places specified elements in it |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getArguments](/slides/php-java/matharray/getarguments/)() | IMathElementCollection | The set of items of the array |
| [getBaseJustification](/slides/php-java/matharray/getbasejustification/)() | int | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [getChildren](/slides/php-java/matharray/getchildren/)() | IMathElement | Get children elements |
| [getMaximumDistribution](/slides/php-java/matharray/getmaximumdistribution/)() | boolean | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution](/slides/php-java/matharray/getobjectdistribution/)() | boolean | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacing](/slides/php-java/matharray/getrowspacing/)() | long | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [getRowSpacingRule](/slides/php-java/matharray/getrowspacingrule/)() | int | The type of vertical spacing between array elements Default: SingleLineGap |
| [setBaseJustification](/slides/php-java/matharray/setbasejustification/)(int) | void | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [setMaximumDistribution](/slides/php-java/matharray/setmaximumdistribution/)(boolean) | void | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setObjectDistribution](/slides/php-java/matharray/setobjectdistribution/)(boolean) | void | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setRowSpacing](/slides/php-java/matharray/setrowspacing/)(long) | void | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [setRowSpacingRule](/slides/php-java/matharray/setrowspacingrule/)(int) | void | The type of vertical spacing between array elements Default: SingleLineGap |
