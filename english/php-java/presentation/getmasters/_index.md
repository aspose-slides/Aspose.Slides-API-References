---
title: getMasters
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 250
url: /php-java/presentation/getmasters/
---

## getMasters()  method

 Returns a list of all master slides that are defined in the presentation.
 Read-only  IMasterSlideCollection.
 

 The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $masterSlide = $slide->getLayoutSlide()->getMasterSlide();
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $masterSlide->getShapes()->addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, $image);
    $pres->save("pres.pptx", SaveFormat.Pptx);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[MasterSlideCollection](../../masterslidecollection)


---


