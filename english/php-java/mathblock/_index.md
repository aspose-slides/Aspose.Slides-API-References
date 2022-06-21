---
title: MathBlock
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathblock/
---

## MathBlock class

 Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
 All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.
 
Example:
 
```php
  $mathBlock = new MathBlock();
```

## Constructors

| Name | Description |
| --- | --- |
| [MathBlock](mathblock)() | Initializes a new instance of the MathBlock class. |
| [MathBlock](mathblock)(IMathElement) | Creates a new mathematical block and puts specified element in it |
| [MathBlock](mathblock)(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) | Creates a new mathematical block and puts specified elements in it |

## Methods

| Name | Description |
| --- | --- |
| [add](add)(IMathElement) | Adds a math element to the end of the collection. |
| [clear](clear)() | Removes all elements from the collection. |
| [contains](contains)(IMathElement) | Determines whether the collection contains a specific value. |
| [copyTo](copyto)(com.aspose.slides.IMathElement[], int) | Copy to specified array. |
| [delimit](delimit)(char) | Delimits child elements with separator character (without the brackets) |
| [enclose](enclose)(char, char) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [enclose](enclose)(char, char, char) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [getChildren](getchildren)() | Get children elements |
| [getCount](getcount)() | Gets the number of child math elements actually contained in the collection. Read-only int. |
| [get_Item](get_item)(int) | Gets or sets IMathElement at the specified index. |
| [indexOf](indexof)(IMathElement) | Determines the index of a specific math element in collection. |
| [insert](insert)(int, IMathElement) | Inserts a MathElement into the collection at the specified index. |
| [isReadOnly](isreadonly)() | Returns false because child elements collection can be modified. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [join](join)(IMathElement) | Joins a mathematical element with this mathematical block |
| [join](join)(String) | Joins a mathematical text with this mathematical block |
| [joinBlock](joinblock)(IMathBlock) | Joins another mathematical block with this one |
| [remove](remove)(IMathElement) | Removes the first occurrence of a specific object from the collection. |
| [removeAt](removeat)(int) | Removes the element at the specified index of the collection. |
| [set_Item](set_item)(int, IMathElement) | Gets or sets IMathElement at the specified index. |
| [toMathArray](tomatharray)() | Puts child elements in a vertical array |
| [writeAsMathMl](writeasmathml)(OutputStream) | Saves content of this MathBlock as MathML |
