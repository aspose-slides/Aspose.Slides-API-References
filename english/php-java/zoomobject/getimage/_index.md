---
title: getImage
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/zoomobject/getimage/
---

## getImage()  method

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
[PPImage](../../ppimage)


---


