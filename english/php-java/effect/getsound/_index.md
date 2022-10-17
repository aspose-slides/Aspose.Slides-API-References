---
title: getSound
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/effect/getsound/
---

## getSound()  method

 Defined embedded sound for effect.
 Read/write  IAudio.
 

 
```php
  $presentation = new Presentation("demo.pptx");
  try {
    $slide = $presentation->getSlides()->get_Item(0);
    // Gets the effects sequence for the slide
    $effectsSequence = $slide->getTimeline()->getMainSequence();
    for ($effect : $effectsSequence) {
      if ($effect->getSound() == null) {
        continue;
      }
      // Extracts the effect sound in byte array
      $audio = $effect->getSound()->getBinaryData();
    }
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
[Audio](../../audio)


---


