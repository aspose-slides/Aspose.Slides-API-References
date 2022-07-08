---
title: getImageType
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/zoomobject/getimagetype/
---

## getImageType()  method

 Gets or sets the image type of a zoom object.
 Read/write  ZoomImageType.
 Default value: Preview
 
 Specifies whether the Zoom object is using the slide preview or a cover image.
 
Next example demonstrates changing Image Type to Preview value. 
 In this case current image of a Zoom object changes to slide image:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1), $image);
    $zoomFrame->setImageType(ZoomImageType.Preview);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
int


---


