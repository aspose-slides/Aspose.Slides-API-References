---
title: FrameTickEventArgs
second_title: Aspose.Slides for Java API Reference
description: Represents arguments of the PresentationPlayer.FrameTick event.
type: docs
weight: 219
url: /java/com.aspose.slides/frametickeventargs/
---
**Inheritance:**
java.lang.Object
```
public class FrameTickEventArgs
```

Represents arguments of the PresentationPlayer.FrameTick event.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick((sender, args) -> {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File(String.format("frame_%d.png", frameNumber[0]++)));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | Get the presentation player |
| [getFrame()](#getFrame--) | Get the current [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Get the presentation player

**Returns:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final BufferedImage getFrame()
```


Get the current [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick((sender, args) -> {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File(String.format("frame_%d.png", frameNumber[0]++)));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.awt.image.BufferedImage
