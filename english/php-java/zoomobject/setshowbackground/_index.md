---
title: setShowBackground
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 210
url: /php-java/zoomobject/setshowbackground/
---

## setShowBackground(boolean value)  method

 Gets or sets value that specifies whether the Zoom will use the background of the destination slide.
 Read/write  boolean.
 Default value: true
 
the example demonstrates removing the background of an image of a Zoom object:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $zoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addZoomFrame(150, 20, 50, 50, $pres->getSlides()->get_Item(1));
    $zoomFrame->setShowBackground(false);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


