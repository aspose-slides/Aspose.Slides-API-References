---
title: insertSectionZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 520
url: /php-java/shapecollection/insertsectionzoomframe/
---

## insertSectionZoomFrame(int index, float x, float y, float width, float height, [../../Section]Section section)  method

 Creates a new Section Zoom object and inserts into to a collection at the specified index.
 

 This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->insertSectionZoomFrame(2, 150, 20, 50, 50, $pres->getSections()->get_Item(1));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index at which Section Zoom frame should be inserted. |
| x | X coordinate of a new Section Zoom frame {@code float}. |
| y | Y coordinate of a new Section Zoom frame {@code float}. |
| width | Width of a new Section Zoom frame {@code float}. |
| height | Height of a new Section Zoom frame {@code float}. |
| section | The slide object referenced by the Section Zoom frame ISection. |

### Returns
Created Section Zoom object ISectionZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


## insertSectionZoomFrame(int index, float x, float y, float width, float height, [../../Section]Section section, [../../PPImage]PPImage image)  method

 Creates a new Section Zoom object and inserts it to a collection at the specified index.
 

 This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->insertSectionZoomFrame(2, 150, 20, 50, 50, $pres->getSections()->get_Item(1), $image);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| index | The zero-based index at which Section Zoom frame should be inserted. |
| x | X coordinate of a new Section Zoom frame {@code float}. |
| y | Y coordinate of a new Section Zoom frame {@code float}. |
| width | Width of a new Section Zoom frame {@code float}. |
| height | Height of a new Section Zoom frame {@code float}. |
| section | The slide object referenced by the Section Zoom frame ISection. |
| image | The image for the referenced slide IPPImage |

### Returns
Created Section Zoom object ISectionZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


