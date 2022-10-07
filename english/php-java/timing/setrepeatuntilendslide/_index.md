---
title: setRepeatUntilEndSlide
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 200
url: /php-java/timing/setrepeatuntilendslide/
---

## setRepeatUntilEndSlide(boolean value)  method

  This attribute specifies if the effect will repeat until the end of the slide.
  Read/write  boolean.
  

  
```php
  $presentation = new Presentation("demo.pptx");
  try {
    // Get the effects sequence for the first slide
    $effectsSequence = $presentation->getSlides()->get_Item(0)->getTimeline()->getMainSequence();
    // Get the first effect of main sequence.
    $effect = $effectsSequence->get_Item(0);
    // Change the effect Timing/Repeat to "Until End of Slide"
    $effect->getTiming()->setRepeatUntilEndSlide(true);
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
void


---


