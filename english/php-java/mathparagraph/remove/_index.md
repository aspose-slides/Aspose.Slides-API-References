---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 170
url: /php-java/mathparagraph/remove/
---

## remove([MathBlock](../../mathblock) mathBlock)  method

 Removes the first occurrence of a specific object from the collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->add(new MathBlock(new MathematicalText("x")));
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->add($block);
  $mathParagraph->remove($block);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../../mathblock) | The object to remove from the collection. |

### Returns
boolean


---


