---
title: contains
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/mathparagraph/contains/
---

## contains(MathBlock mathBlock)  method

 Determines whether the collection contains a specific value.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->add($block);
  $contains = $mathParagraph->contains($block);
```

### Parameters

| Name | Description |
| --- | --- |
| mathBlock | The object to locate in the collection. |

### Returns
true if mathBlock is found in the collection; otherwise, false.


---


