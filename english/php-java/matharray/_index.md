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
| [MathArray](matharray)([MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathLimit](../mathlimit)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathMatrix](../mathmatrix)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathBlock](../mathblock)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathRadical](../mathradical)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathArray](../matharray)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathDelimiter](../mathdelimiter)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathNaryOperator](../mathnaryoperator)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathAccent](../mathaccent)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathBorderBox](../mathborderbox)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathGroupingCharacter](../mathgroupingcharacter)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathBar](../mathbar)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathSuperscriptElement](../mathsuperscriptelement)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathFunction](../mathfunction)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathSubscriptElement](../mathsubscriptelement)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathFraction](../mathfraction)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathematicalText](../mathematicaltext)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathBox](../mathbox)) | Creates a mathematical array and places the specified element in it |
| [MathArray](matharray)([MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Creates a mathematical array and places the specified element in it |
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
