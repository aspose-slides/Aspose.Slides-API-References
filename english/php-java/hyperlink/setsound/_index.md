---
title: setSound
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 310
url: /php-java/hyperlink/setsound/
---

## setSound([Audio](../../audio) value)  method

 Represents the playing sound of the hyperlink.
 Read/write  IAudio.
 

 
```php
  $presentation = new Presentation("demo.pptx");
  try {
    $slide = $presentation->getSlides()->get_Item(0);
    // Get the first shape hyperlink
    $link = $presentation->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getHyperlinkClick();
    if ($link->getSound() != null) {
      // Extract the hyperlink sound in byte array
      $audioData = $link->getSound()->getBinaryData();
    }
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
void


---


