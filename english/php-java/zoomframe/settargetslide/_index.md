---
title: setTargetSlide
type: docs
weight: 20
url: /php-java/zoomframe/settargetslide/
---

# setTargetSlide(com.aspose.slides.ISlide) method

 Gets or sets the slide object that the Slide Zoom object links to.
 Read/write  ISlide.
 
Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
 
```php
  $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
  $zoomFrame->setTargetSlide($pres->getSlides()->get_Item(2));
```

##  Returns
ISlide

