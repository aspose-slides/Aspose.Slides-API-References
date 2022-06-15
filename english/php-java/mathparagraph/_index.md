---
title: MathParagraph
type: docs
weight: 0
url: /php-java/mathparagraph/
---

# MathParagraph class

 Mathematical paragraph that is a container for mathematical blocks (IMathBlock)
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->setJustification(MathJustification.LeftJustified);
```

## Constructors

| name | description |
| --- | --- |
| [MathParagraph](/php-java/mathparagraph/mathparagraph/)() | Initializes a new instance of the MathParagraph class. |
| [MathParagraph](/php-java/mathparagraph/mathparagraph/)(IMathBlock) | Initializes a new instance of the MathParagraph class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/php-java/mathparagraph/add/)(IMathBlock) | void | Adds IMathBlock to the end of collection. |
| [clear](/php-java/mathparagraph/clear/)() | void | Removes all elements from the collection. |
| [contains](/php-java/mathparagraph/contains/)(IMathBlock) | boolean | Determines whether the collection contains a specific value. |
| [getCount](/php-java/mathparagraph/getcount/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
| [getJustification](/php-java/mathparagraph/getjustification/)() | int | Paragraph Justification Default value: CenteredAsGroup |
| [get_Item](/php-java/mathparagraph/get_item/)(int) | IMathBlock | Gets the item at the specified index. Read-only IMathBlock. |
| [indexOf](/php-java/mathparagraph/indexof/)(IMathBlock) | int | Determines the index of a specific IMathBlock in collection. |
| [insert](/php-java/mathparagraph/insert/)(int, IMathBlock) | void | Inserts IMathBlock into the collection at the specified index. |
| [iterator](/php-java/mathparagraph/iterator/)() | IGenericEnumerator |  |
| [iteratorJava](/php-java/mathparagraph/iteratorjava/)() | IEnumerator |  |
| [remove](/php-java/mathparagraph/remove/)(IMathBlock) | boolean | Removes the first occurrence of a specific object from the collection. |
| [removeAt](/php-java/mathparagraph/removeat/)(int) | void | Removes an item at the specified index of the collection. |
| [setJustification](/php-java/mathparagraph/setjustification/)(int) | void | Paragraph Justification Default value: CenteredAsGroup |
| [set_Item](/php-java/mathparagraph/set_item/)(int, IMathBlock) | void | Gets the item at the specified index. Read-only IMathBlock. |
| [writeAsMathMl](/php-java/mathparagraph/writeasmathml/)(OutputStream) | void | Saves content of this MathParagraph as MathML |
