---
title: addZoomFrame
type: docs
weight: 270
url: /php-java/shapecollection/addzoomframe/
---

# addZoomFrame(float, float, float, float, com.aspose.slides.ISlide) method

 Adds a new Zoom object to the end of a collection.
 

 This example demonstrates adding a Zoom object to the end of a collection
 (assume that there are at least two slides in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new Zoom frame float. |
| y | Y coordinate of a new Zoom frame float. |
| width | Width of a new Zoom frame float. |
| height | Height of a new Zoom frame float. |
| slide | The slide object referenced by the Zoom frame ISlide. |

##  Returns
Created Zoom object IZoomFrame.

##  Exception
ArgumentException Referenced slide does not belong to the current presentation.


# addZoomFrame(float, float, float, float, com.aspose.slides.ISlide, com.aspose.slides.IPPImage) method

 Adds a new Zoom object to the end of a collection.
 

 This example demonstrates adding a Zoom object to the end of a collection
 (assume that there are at least two slides in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $image = $pres->getImages()->addImage($imageBytes);
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1), $image);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| x | X coordinate of a new Zoom frame float. |
| y | Y coordinate of a new Zoom frame float. |
| width | Width of a new Zoom frame float. |
| height | Height of a new Zoom frame float. |
| slide | The slide object referenced by the Zoom frame ISlide. |
| image | The image for the referenced slide IPPImage |

##  Returns
Created Zoom object IZoomFrame.

##  Exception
ArgumentException Referenced slide does not belong to the current presentation.

