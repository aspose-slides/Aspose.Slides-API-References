---
title: set_Item
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 170
url: /php-java/mathparagraph/set_item/
---

## set_Item(int index, [MathBlock](../../mathblock) value)  method

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
| value | int | The block of a mathematical text. |
| index | MathBlock | The zero-based index of the item to get |

### Returns
IMathBlock


---


