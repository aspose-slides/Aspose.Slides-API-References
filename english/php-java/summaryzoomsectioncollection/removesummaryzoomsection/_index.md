---
title: removeSummaryZoomSection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/summaryzoomsectioncollection/removesummaryzoomsection/
---

## removeSummaryZoomSection([Section](../../section) section)  method

 Remove Summary Zoom Section object from the collection.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $collection->removeSummaryZoomSection($pres->getSections()->get_Item(1));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | Section | Section for which the Summary Zoom Section element is to be removed ISection. |


---


