---
title: getFillFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/shape/getfillformat/
---

## getFillFormat()  method

 Returns the FillFormat object that contains fill formatting properties for a shape.
 Note: can return null for certain types of shapes which don't have fill properties.
 Read-only  IFillFormat.
 

 The following example shows how to change the accent color for a theme of PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
    $shape->getFillFormat()->setFillType(FillType.Solid);
    $shape->getFillFormat()->getSolidFillColor()->setSchemeColor(SchemeColor.Accent4);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[FillFormat](../../fillformat)


---


