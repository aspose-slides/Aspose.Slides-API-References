---
title: addSummaryZoomSection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/summaryzoomsectioncollection/addsummaryzoomsection/
---

## addSummaryZoomSection([../../Section]Section section)  method

 Creates new Summary Zoom Section object and add it to the collection
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $newZoomSection = $collection->addSummaryZoomSection($pres->getSections()->get_Item(3));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| section | Section for a new Summary Zoom Section element ISection If an element for this section already exists in the collection, the existing element is returned. |

### Returns
Added ISummaryZoomFrame element

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


