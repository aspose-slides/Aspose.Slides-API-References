---
title: insert
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 130
url: /php-java/mathparagraph/insert/
---

## insert(int index, [MathBlock](../../mathblock) mathBlock)  method

 Inserts IMathBlock into the collection at the specified index.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->insert(0, $block);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which an item should be inserted. |
| mathBlock | [MathBlock](../../mathblock) | The IMathBlock to insert. |

### Returns
void


---


