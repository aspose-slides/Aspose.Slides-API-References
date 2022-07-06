---
title: insert
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/mathparagraph/insert/
---

## insert(int index, [../../MathBlock]MathBlock mathBlock)  method

 Inserts IMathBlock into the collection at the specified index.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $block = new MathBlock(new MathematicalText("y"));
  $mathParagraph->insert(0, $block);
```

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index at which an item should be inserted. |
| mathBlock | The IMathBlock to insert. |


---


