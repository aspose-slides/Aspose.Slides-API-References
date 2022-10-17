---
title: getAdvanceAfter
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/slideshowtransition/getadvanceafter/
---

## getAdvanceAfter()  method

 This attribute specifies if the slideshow will move to the next slide after a certain time.
 Read/write  boolean.
 

 
```php
  $pres = new Presentation("demo.pptx");
  try {
    // Get the first slide Transition
    $slideTransition = $pres->getSlides()->get_Item(0)->getSlideShowTransition();
    // Check if the Advance Slide After flag is checked
    if ($slideTransition->getAdvanceAfter()) {
      // Get the Advance Slide After Time value
      $advanceAfterTime = $slideTransition->getAdvanceAfterTime();
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


