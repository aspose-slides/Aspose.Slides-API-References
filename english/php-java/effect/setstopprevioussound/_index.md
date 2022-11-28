---
title: setStopPreviousSound
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 150
url: /php-java/effect/setstopprevioussound/
---

## setStopPreviousSound(boolean value)  method

 This attribute specifies if the animation effect stops the previous sound.
 Read/write  boolean.
 

 
```php
  $presentation = new Presentation("demo.pptx");
  try {
    // Get the first effect of the first slide.
    $firstSlideEffect = $presentation->getSlides()->get_Item(0)->getTimeline()->getMainSequence()->get_Item(0);
    // Get the first effect of the second slide.
    $secondSlideEffect = $presentation->getSlides()->get_Item(1)->getTimeline()->getMainSequence()->get_Item(0);
    if ($firstSlideEffect->getSound() != null) {
      // Change the second effect Enhancements/Sound to "Stop Previous Sound"
      $secondSlideEffect->setStopPreviousSound(true);
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


