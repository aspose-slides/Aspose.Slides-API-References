---
title: getFrameIndex
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/presentationplayer/getframeindex/
---

## getFrameIndex()  method

 Gets the frame index.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($pres);
    try {
      $player = new PresentationPlayer($animationsGenerator, 33);
      try {
        $player->setFrameTick(( sender, args) -> {
          try {
            ImageIO->write($args->getFrame(), "PNG", new java.io.File("frame_" + $sender->getFrameIndex() + ".png"));
          } catch (JavaException $e) {
            throw new <e>RuntimeException();
          }
        });
        $animationsGenerator->run($pres->getSlides());
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
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
int


---


