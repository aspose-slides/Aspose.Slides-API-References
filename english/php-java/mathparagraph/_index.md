---
title: MathParagraph
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathparagraph/
---

## MathParagraph class

 Mathematical paragraph that is a container for mathematical blocks (IMathBlock)
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->setJustification(MathJustification.LeftJustified);
```

## Constructors

| Name | Description |
| --- | --- |
| [MathParagraph](mathparagraph)() | Initializes a new instance of the MathParagraph class. |
| [MathParagraph](mathparagraph)([MathBlock](../mathblock)) | Initializes a new instance of the MathParagraph class. |

## Methods

| Name | Description |
| --- | --- |
| [add](add)([MathBlock](../mathblock)) | Adds IMathBlock to the end of collection. |
| [clear](clear)() | Removes all elements from the collection. |
| [contains](contains)([MathBlock](../mathblock)) | Determines whether the collection contains a specific value. |
| [getCount](getcount)() | Gets the number of elements actually contained in the collection. Read-only int. |
| [getJustification](getjustification)() | Paragraph Justification Default value: CenteredAsGroup |
| [get_Item](get_item)(int) | Gets the item at the specified index. Read-only IMathBlock. |
| [indexOf](indexof)([MathBlock](../mathblock)) | Determines the index of a specific IMathBlock in collection. |
| [insert](insert)(int, [MathBlock](../mathblock)) | Inserts IMathBlock into the collection at the specified index. |
| [iterator](iterator)() |  |
| [iteratorJava](iteratorjava)() |  |
| [remove](remove)([MathBlock](../mathblock)) | Removes the first occurrence of a specific object from the collection. |
| [removeAt](removeat)(int) | Removes an item at the specified index of the collection. |
| [setJustification](setjustification)(int) | Paragraph Justification Default value: CenteredAsGroup |
| [set_Item](set_item)(int, [MathBlock](../mathblock)) | Gets the item at the specified index. Read-only IMathBlock. |
| [writeAsMathMl](writeasmathml)(OutputStream) | Saves content of this MathParagraph as MathML |
