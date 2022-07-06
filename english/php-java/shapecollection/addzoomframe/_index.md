---
title: addZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 270
url: /php-java/shapecollection/addzoomframe/
---

## addZoomFrame(float x, float y, float width, float height, [Slide](../../Slide) slide)  method

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

### Parameters

| Name | Description |
| --- | --- |
| x | X coordinate of a new Zoom frame {@code float}. |
| y | Y coordinate of a new Zoom frame {@code float}. |
| width | Width of a new Zoom frame {@code float}. |
| height | Height of a new Zoom frame {@code float}. |
| slide | The slide object referenced by the Zoom frame ISlide. |

### Returns
Created Zoom object IZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


## addZoomFrame(float x, float y, float width, float height, [Slide](../../Slide) slide, [PPImage](../../PPImage) image)  method

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

### Parameters

| Name | Description |
| --- | --- |
| x | X coordinate of a new Zoom frame {@code float}. |
| y | Y coordinate of a new Zoom frame {@code float}. |
| width | Width of a new Zoom frame {@code float}. |
| height | Height of a new Zoom frame {@code float}. |
| slide | The slide object referenced by the Zoom frame ISlide. |
| image | The image for the referenced slide IPPImage |

### Returns
Created Zoom object IZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


