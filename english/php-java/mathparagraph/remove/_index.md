---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 140
url: /php-java/mathparagraph/remove/
---

## remove([MathBlock](../../MathBlock) mathBlock)  method

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

| Name | Description |
| --- | --- |
| mathBlock | The object to remove from the collection. |

### Returns
true if mathBlock was successfully removed from the collection; otherwise, false. This method also returns false if mathBlock is not found in the original collection.


---


