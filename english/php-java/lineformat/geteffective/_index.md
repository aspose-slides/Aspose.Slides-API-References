---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/lineformat/geteffective/
---

## getEffective()  method

 Gets effective line formatting data with the inheritance applied.
 

 This example demonstrates getting shape's effective line format properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $effectiveLineFormat = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getLineFormat()->getEffective();
    echo("Style: " + $effectiveLineFormat->getStyle());
    echo("Width: " + $effectiveLineFormat->getWidth());
    echo("Fill type: " + $effectiveLineFormat->getFillFormat()->getFillType());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[LineFormatEffectiveData](../../lineformateffectivedata)


---


