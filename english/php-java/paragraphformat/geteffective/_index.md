---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/paragraphformat/geteffective/
---

## getEffective()  method

 Gets effective paragraph formatting data with the inheritance applied.
 

 This example demonstrates getting some effective paragraph format properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $effectiveParagraphFormat = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getParagraphFormat()->getEffective();
    echo("Text alignment: " + $effectiveParagraphFormat->getAlignment());
    echo("Indent: " + $effectiveParagraphFormat->getIndent());
    echo("Bullet type: " + $effectiveParagraphFormat->getBullet()->getType());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
A IParagraphFormatEffectiveData.


---


