---
title: clear
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/mathparagraph/clear/
---

## clear()  method

 Removes all elements from the collection.
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->add(new MathBlock(new MathematicalText("block1")));
  $mathParagraph->add(new MathBlock(new MathematicalText("block2")));
  $mathParagraph->clear();
```

### Returns
void


---


