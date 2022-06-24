---
title: getReturnToParent
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 30
url: /php-java/zoomobject/getreturntoparent/
---

## getReturnToParent() method

 Gets or sets the navigation behavior in slideshow.
 Read/write  boolean.
 Default value: false
 
 True value of the property specifies return to parent navigation behavior in slideshow.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
    $zoomFrame->setReturnToParent(true);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


