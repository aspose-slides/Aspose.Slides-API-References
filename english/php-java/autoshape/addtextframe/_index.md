---
title: addTextFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/autoshape/addtextframe/
---

## addTextFrame(String text)  method

 Adds a new TextFrame to a shape.
 If shape already has TextFrame then simply changes its text.
 

 The following sample code shows how to add watermark text in PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $watermarkShape = $slide->getShapes()->addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
    $watermarkTextFrame = $watermarkShape->addTextFrame("Watermark");
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | Default text for a new TextFrame. |

### Returns
[TextFrame](../../textframe)


---


