---
title: getSummarySection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/summaryzoomsectioncollection/getsummarysection/
---

## getSummarySection([Section](../../section) section)  method

 Returns Summary Zoom Section element for the given section.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $selectedObject = $collection->getSummarySection($pres->getSections()->get_Item(2));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | Section to find ISection |

### Returns
[SummaryZoomSection](../../summaryzoomsection)


---


