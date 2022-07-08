---
title: getJustification
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/mathparagraph/getjustification/
---

## getJustification()  method

 Paragraph Justification 
 Default value: CenteredAsGroup
 
Example:
 
```php
  $shape = $slide->getShapes()->addMathShape($x, $y, $width, $height);
  $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
  $mathParagraph->setJustification(MathJustification.LeftJustified);
```

### Returns
int


---


