---
title: MathArray
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/matharray/
---

## MathArray class

 Specifies a vertical array of equations or any mathematical objects 
 
Example:
 
```php
  $mathArray = new MathArray(new MathematicalText("item1"));
```

## Constructors

| Name | Description |
| --- | --- |
| [MathArray](matharray)(MathLeftSubSuperscriptElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathLimit) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathMatrix) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathBlock) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathRadical) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathArray) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathDelimiter) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathAccent) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathNaryOperator) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathBorderBox) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathGroupingCharacter) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathBar) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathFunction) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathSuperscriptElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathSubscriptElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathFraction) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathematicalText) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(BaseScript) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathBox) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathElementBase) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(MathRightSubSuperscriptElement) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) | Creates a mathematical array and places specified elements in it |

## Methods

| Name | Description |
| --- | --- |
| [getArguments](getarguments)() | The set of items of the array |
| [getBaseJustification](getbasejustification)() | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [getChildren](getchildren)() | Get children elements |
| [getMaximumDistribution](getmaximumdistribution)() | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution](getobjectdistribution)() | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacing](getrowspacing)() | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [getRowSpacingRule](getrowspacingrule)() | The type of vertical spacing between array elements Default: SingleLineGap |
| [setBaseJustification](setbasejustification)(int) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center |
| [setMaximumDistribution](setmaximumdistribution)(boolean) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setObjectDistribution](setobjectdistribution)(boolean) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setRowSpacing](setrowspacing)(long) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0 |
| [setRowSpacingRule](setrowspacingrule)(int) | The type of vertical spacing between array elements Default: SingleLineGap |
