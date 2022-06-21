---
title: getPlayAcrossSlides
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 90
url: /php-java/audioframe/getplayacrossslides/
---

## getPlayAcrossSlides() method

  Determines whether audio is playing across the slides.
  Read/write  boolean.
  

  
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    // Add Audio Frame
    $audioFrame = $slide->getShapes()->addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
    // Set Audio to play across the slides
    $audioFrame->setPlayAcrossSlides(true);
    // Set Audio to automatically rewind to start after playing
    $audioFrame->setRewindAudio(true);
    $pres->save("AudioFrame_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


