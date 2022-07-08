---
title: indexOf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/summaryzoomsectioncollection/indexof/
---

## indexOf([SummaryZoomSection](../../summaryzoomsection) summaryZoomSection)  method

 Returns an index of the specified SummaryZoomSection object.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $selectedObject = $collection->getSummarySection($pres->getSections()->get_Item(2));
    $idx = $collection->indexOf($selectedObject);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [SummaryZoomSection](../../summaryzoomsection) | SummaryZoomSection object to find ISummaryZoomSection. |

### Returns
int


---


