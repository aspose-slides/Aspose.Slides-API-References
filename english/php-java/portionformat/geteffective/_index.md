---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/portionformat/geteffective/
---

## getEffective()  method

 Gets effective portion formatting data with the inheritance applied.
 

 This example demonstrates getting some effective portion format properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $effectivePortionFormat = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->get_Item(0)->getPortionFormat()->getEffective();
    echo("Latin font: " + $effectivePortionFormat->getLatinFont()->getFontName());
    echo("Font height: " + $effectivePortionFormat->getFontHeight());
    echo("Fill type: " + $effectivePortionFormat->getFillFormat()->getFillType());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns



---


