---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/mathparagraph/add/
---

## add([MathBlock](../../mathblock) mathBlock)  method

 Adds IMathBlock to the end of collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->add(new MathBlock(new MathematicalText("x")));
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| mathBlock | MathBlock | A mathematical block that will be added to the end of the collection |


---


