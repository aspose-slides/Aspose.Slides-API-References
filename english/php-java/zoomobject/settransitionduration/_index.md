---
title: setTransitionDuration
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 100
url: /php-java/zoomobject/settransitionduration/
---

## setTransitionDuration(float) method

 Gets or sets the duration of the transition between Zoom and slide.
 Read/write  float.
 Default value: 1.0f
 
 If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition.
 
the example demonstrates changing the duration of the transition between Zoom and slide:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
    $zoomFrame->setTransitionDuration(2.5);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
float


---


