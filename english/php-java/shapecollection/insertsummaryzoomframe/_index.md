---
title: insertSummaryZoomFrame
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 540
url: /php-java/shapecollection/insertsummaryzoomframe/
---

## insertSummaryZoomFrame(int, float, float, float, float) method

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

| Name | Description |
| --- | --- |
| index | The zero-based index at which Section Zoom frame should be inserted. |
| x | X coordinate of a new Section Zoom frame float. |
| y | Y coordinate of a new Section Zoom frame float. |
| width | Width of a new Section Zoom frame float. |
| height | Height of a new Section Zoom frame float. This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. |

### Returns
Created Summary Zoom object ISummaryZoomFrame.

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | There are no sections in the presentation, or the target slide does not belong to any section. |


---


