---
title: indexOf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 120
url: /php-java/mathparagraph/indexof/
---

## indexOf([MathBlock](../../mathblock) mathBlock)  method

 Determines the index of a specific IMathBlock in collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->add($block);
  $index = $mathParagraph->indexOf($block);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../../mathblock) | The item to locate in the collection. |

### Returns
int


---


