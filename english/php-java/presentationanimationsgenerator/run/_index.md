---
title: run
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/presentationanimationsgenerator/run/
---

## run(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> slides)  method

 Run the animation events generation for each slide.
 

 
```php
  $presentation = new Presentation("animated.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($presentation->getSlideSize()->getSize());
    try {
      $player = new PresentationPlayer($animationsGenerator, 33);
      try {
        $animationsGenerator->setNewAnimation(( animationPlayer) -> {
          // handle new animation
        });
        $player->setFrameTick(( sender, args) -> {
          // handle frame tick within the new animation
        });
        $animationsGenerator->run($presentation->getSlides());
      } finally {
        if ($player != null) {
          $player->dispose();
        }
      }
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


## run(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> slides, int fps, [PresentationPlayer.FrameTick](../../presentationplayer.frametick) onFrame)  method

 Run the animation events generation for each slide.
 

 
```php
  $presentation = new Presentation("animated.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($presentation->getSlideSize()->getSize());
    try {
      $animationsGenerator->run($presentation->getSlides(), 33, ( player, playerArgs) -> {
        $player->setFrameTick(( sender, args) -> {
          try {
            ImageIO->write($args->getFrame(), "PNG", new java.io.File("frame_" + $sender->getFrameIndex() + ".png"));
          } catch (JavaException $e) {
            throw new <e>RuntimeException();
          }
        });
      });
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


