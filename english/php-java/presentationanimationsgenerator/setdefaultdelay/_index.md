---
title: setDefaultDelay
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/presentationanimationsgenerator/setdefaultdelay/
---

## setDefaultDelay(int value)  method

 Gets or sets default delay time [ms].
 

 
```php
  $presentation = new Presentation("animated.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($presentation->getSlideSize()->getSize());
    try {
      $animationsGenerator->setDefaultDelay(1000);// 1s

      // ...
      $animationsGenerator->run($presentation->getSlides());
    } finally {
      if ($animationsGenerator != null) {
        $animationsGenerator->dispose();
      }
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


