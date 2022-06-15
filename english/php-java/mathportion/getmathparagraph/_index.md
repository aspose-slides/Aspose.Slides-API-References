---
title: getMathParagraph
type: docs
weight: 20
url: /php-java/mathportion/getmathparagraph/
---

# getMathParagraph() method

 Math paragraph
 
Example:
 
```php
  $pres = new Presentation();
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->addMathShape(0, 0, 300, 50);
    $mathParagraph = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getMathParagraph();
    $mathParagraph->add(new MathBlock(new MathematicalText("x+y")));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


