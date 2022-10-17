---
title: insertSummaryZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 540
url: /php-java/shapecollection/insertsummaryzoomframe/
---

## insertSummaryZoomFrame(int index, float x, float y, float width, float height)  method

 Creates a new Summary Zoom object and inserts it to a collection at the specified index.
 

 This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
 (assume that there are at least two sections in the "Presentation.pptx" presentation):
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->insertSummaryZoomFrame(2, 150, 20, 50, 50);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

### Returns
[SummaryZoomFrame](../../summaryzoomframe)

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


