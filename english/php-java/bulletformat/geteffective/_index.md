---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/bulletformat/geteffective/
---

## getEffective()  method

 Gets effective bullet formatting data with the inheritance applied.
 

 This example demonstrates getting some effective bullet format properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $effectiveBulletFormat = $shape->getTextFrame()->getParagraphs()->get_Item(0)->getParagraphFormat()->getBullet()->getEffective();
    echo("Bullet type: " + $effectiveBulletFormat->getType());
    if ($effectiveBulletFormat->getType() == BulletType::Numbered) {
      echo("Numbered style: " + $effectiveBulletFormat->getNumberedBulletStyle());
      echo("Starting number: " + $effectiveBulletFormat->getNumberedBulletStartWith());
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
A IBulletFormatEffectiveData.


---


