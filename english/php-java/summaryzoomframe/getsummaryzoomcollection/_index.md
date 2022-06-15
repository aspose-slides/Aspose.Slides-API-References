---
title: getSummaryZoomCollection
type: docs
weight: 20
url: /php-java/summaryzoomframe/getsummaryzoomcollection/
---

# getSummaryZoomCollection() method

 Gets  ISummaryZoomSectionCollection for the Summary Zoom Frame object.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
ISummaryZoomSectionCollection


