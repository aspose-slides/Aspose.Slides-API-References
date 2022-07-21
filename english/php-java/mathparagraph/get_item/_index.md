---
title: get_Item
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/mathparagraph/get_item/
---

## get_Item(int index)  method

 Gets the item at the specified index.
 Read-only  IMathBlock.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->add(new MathBlock(new MathematicalText("block1")));
  $mathParagraph->add(new MathBlock(new MathematicalText("block2")));
  $block = $mathParagraph->get_Item(1);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to get |

### Returns
[MathBlock](../../mathblock)


---


