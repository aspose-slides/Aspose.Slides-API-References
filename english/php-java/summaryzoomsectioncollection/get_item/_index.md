---
title: get_Item
type: docs
weight: 60
url: /php-java/summaryzoomsectioncollection/get_item/
---

# get_Item(int) method

 Gets the element at the specified index.
 Read-only  ISummaryZoomSection.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $zoomSection = $collection->get_Item(1);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
ISummaryZoomSection

