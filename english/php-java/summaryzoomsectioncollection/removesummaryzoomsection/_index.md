---
title: removeSummaryZoomSection
type: docs
weight: 110
url: /php-java/summaryzoomsectioncollection/removesummaryzoomsection/
---

# removeSummaryZoomSection(com.aspose.slides.ISection) method

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

##  Parameters

| name | description |
| --- | --- |
| section | Section for which the Summary Zoom Section element is to be removed ISection. |


