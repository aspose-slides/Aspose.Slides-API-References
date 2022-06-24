---
title: setJustification
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 160
url: /php-java/mathparagraph/setjustification/
---

## setJustification(int) method

 Paragraph Justification 
 Default value: CenteredAsGroup
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->setJustification(MathJustification.LeftJustified);
```


---


