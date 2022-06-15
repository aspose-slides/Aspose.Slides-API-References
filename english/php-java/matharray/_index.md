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
| [MathArray](/php-java/matharray/matharray/)(IMathElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](/php-java/matharray/matharray/)(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) | Creates a mathematical array and places specified elements in it |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getArguments](/php-java/matharray/getarguments/)() | IMathElementCollection | The set of items of the array |
| [getBaseJustification](/php-java/matharray/getbasejustification/)() | int | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [getChildren](/php-java/matharray/getchildren/)() | IMathElement | Get children elements |
| [getMaximumDistribution](/php-java/matharray/getmaximumdistribution/)() | boolean | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution](/php-java/matharray/getobjectdistribution/)() | boolean | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacing](/php-java/matharray/getrowspacing/)() | long | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [getRowSpacingRule](/php-java/matharray/getrowspacingrule/)() | int | The type of vertical spacing between array elements Default: SingleLineGap |
| [setBaseJustification](/php-java/matharray/setbasejustification/)(int) | void | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [setMaximumDistribution](/php-java/matharray/setmaximumdistribution/)(boolean) | void | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setObjectDistribution](/php-java/matharray/setobjectdistribution/)(boolean) | void | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setRowSpacing](/php-java/matharray/setrowspacing/)(long) | void | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [setRowSpacingRule](/php-java/matharray/setrowspacingrule/)(int) | void | The type of vertical spacing between array elements Default: SingleLineGap |
