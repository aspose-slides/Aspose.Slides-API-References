---
title: setIncludeHiddenSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 120
url: /php-java/presentationanimationsgenerator/setincludehiddenslides/
---

## setIncludeHiddenSlides(boolean value)  method

 Get or sets if hidden slides should be included.
 

 
```php
  $presentation = new Presentation("animated.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($presentation->getSlideSize()->getSize());
    try {
      $animationsGenerator->setIncludeHiddenSlides(false);
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


