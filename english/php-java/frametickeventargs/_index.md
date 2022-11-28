---
title: FrameTickEventArgs
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/frametickeventargs/
---

## FrameTickEventArgs class

 Represents arguments of the  PresentationPlayer.FrameTick event.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $animationsGenerator = new PresentationAnimationsGenerator($pres);
    try {
      $player = new PresentationPlayer($animationsGenerator, 33);
      try {
        $frameNumber = new int[]{ 0 };
        $player->setFrameTick(( sender, args) -> {
          try {
            ImageIO->write($args->getFrame(), "PNG", new java.io.File(String->format("frame_%d.png", $frameNumber[0]++)));
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

## Methods

| Name | Description |
| --- | --- |
| [getFrame](getframe)() | Get the current PresentationPlayer frame. |
| [getPlayer](getplayer)() | Get the presentation player |
