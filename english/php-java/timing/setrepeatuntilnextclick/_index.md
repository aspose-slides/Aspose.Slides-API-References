---
title: setRepeatUntilNextClick
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 210
url: /php-java/timing/setrepeatuntilnextclick/
---

## setRepeatUntilNextClick(boolean value)  method

  This attribute specifies if the effect will repeat until the next click.
  Read/write  boolean.
  

  
```php
  $presentation = new Presentation("demo.pptx");
  try {
    // Get the effects sequence for the first slide
    $effectsSequence = $presentation->getSlides()->get_Item(0)->getTimeline()->getMainSequence();
    // Get the first effect of main sequence.
    $effect = $effectsSequence->get_Item(0);
    // Change the effect Timing/Repeat to "Until Next Click"
    $effect->getTiming()->setRepeatUntilNextClick(true);
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
void


---


