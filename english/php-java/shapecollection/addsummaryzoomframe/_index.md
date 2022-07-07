---
title: addSummaryZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 230
url: /php-java/shapecollection/addsummaryzoomframe/
---

## addSummaryZoomFrame(float x, float y, float width, float height)  method

 Adds a new Summary Zoom object to the end of a collection.
 

 This example demonstrates adding a Summary Zoom object to the end of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSummaryZoomFrame(150, 20, 500, 250);
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
| height | float | Height of a new Section Zoom frame {@code float}. This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

### Returns
Created Summary Zoom object ISummaryZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


