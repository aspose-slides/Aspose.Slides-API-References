---
title: setNewAnimation
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 130
url: /php-java/presentationanimationsgenerator/setnewanimation/
---

## setNewAnimation([PresentationAnimationsGenerator.NewAnimation](../../presentationanimationsgenerator.newanimation) anim)  method

 Set a new animation event.
 

 
```php
  $presentation = new Presentation("SimpleAnimations.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($presentation->getSlideSize()->getSize());
    try {
      $animationsGenerator->setNewAnimation(( animationPlayer) -> {
        $System.out->println(String->format("Animation total duration: %f", $animationPlayer->getDuration()));
      });
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

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| anim | [PresentationAnimationsGenerator.NewAnimation](../../presentationanimationsgenerator.newanimation) | Animation event. |

### Returns
void


---


