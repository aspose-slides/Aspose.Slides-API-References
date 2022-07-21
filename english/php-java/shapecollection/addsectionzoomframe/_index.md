---
title: addSectionZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 450
url: /php-java/shapecollection/addsectionzoomframe/
---

## addSectionZoomFrame(float x, float y, float width, float height, [Section](../../section) section)  method

 Adds a new Section Zoom object to the end of a collection.
 

 This example demonstrates adding a Section Zoom object to the end of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSectionZoomFrame(150, 20, 50, 50, $pres->getSections()->get_Item(1));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../../section) | The section object referenced by the Section Zoom frame ISection. |

### Returns
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


## addSectionZoomFrame(float x, float y, float width, float height, [Section](../../section) section, [PPImage](../../ppimage) image)  method

 Adds a new Section Zoom object to the end of a collection with a predefined image.
 

 This example demonstrates adding a Section Zoom object to the end of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $image = $pres->getImages()->addImage(Files->readAllBytes(Paths->get("image.png")));
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSectionZoomFrame(150, 20, 50, 50, $pres->getSections()->get_Item(1), $image);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The section object referenced by the Section Zoom frame ISection. |
| image | [PPImage](../../ppimage) | The image for the referenced slide IPPImage |

### Returns
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


