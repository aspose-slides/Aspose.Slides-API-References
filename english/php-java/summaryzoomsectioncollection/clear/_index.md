---
title: clear
type: docs
weight: 20
url: /php-java/summaryzoomsectioncollection/clear/
---

# clear() method

 Removes all SummaryZoomSection objects from the collection.
 
The example demonstrates getting Summary Zoom Section element by index:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(1)->getShapes()->get_Item(0);
    $collection = $zoomFrame->getSummaryZoomCollection();
    $collection->clear();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


