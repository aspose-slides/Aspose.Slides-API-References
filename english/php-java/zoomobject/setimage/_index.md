---
title: setImage
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 60
url: /php-java/zoomobject/setimage/
---

## setImage(com.aspose.slides.IPPImage) method

 Gets or sets image for zoom object.
 Read/write  IPPImage.
 
the example demonstrates changing an image of a Zoom object:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $zoomFrame->setImage($image);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
IPPImage


---


