---
title: shapes
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/collect/shapes/
---

## shapes([../../Presentation]Presentation pres)  method

 Collects all instances of  Shape in the  Presentation. 
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    for ($shape : Collect->shapes($pres)) {
      // if the shape is AutoShape, add a black solid border
      if ($shape instanceof AutoShape) {
        $autoShape = $shape;
        $autoShape->getLineFormat()->setStyle(LineStyle.Single);
        $autoShape->getLineFormat()->setWidth(10.0);
        $autoShape->getLineFormat()->getFillFormat()->setFillType(FillType.Solid);
        $autoShape->getLineFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::black);
      }
    }
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| pres | Presentation to collect shapes |

### Returns
Presentation


---


