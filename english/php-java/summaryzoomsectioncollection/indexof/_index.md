---
title: indexOf
type: docs
weight: 70
url: /php-java/summaryzoomsectioncollection/indexof/
---

# indexOf(com.aspose.slides.ISummaryZoomSection) method

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

##  Parameters

| name | description |
| --- | --- |
| summaryZoomSection | SummaryZoomSection object to find ISummaryZoomSection. |

##  Returns
Index of a SummaryZoomSection object or -1 if SummaryZoomSection object not from this collection.

