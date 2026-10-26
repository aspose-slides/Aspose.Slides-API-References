---
title: FrameTickEventArgs
second_title: Aspose.Slides for Java API Referencia
description: A PresentationPlayer.FrameTick esemény argumentumait képviseli.
type: docs
url: /hu/com.aspose.slides/frametickeventargs/
---
**Öröklés:**
java.lang.Object
```
public class FrameTickEventArgs
```

A PresentationPlayer.FrameTick esemény argumentumait képviseli.

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
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
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

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPlayer()](#getPlayer--) | A prezentáció lejátszó lekérése |
| [getFrame()](#getFrame--) | Az aktuális [PresentationPlayer](../../com.aspose.slides/presentationplayer) keret lekérése |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

A prezentáció lejátszó lekérése

**Visszatér:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

Az aktuális [PresentationPlayer](../../com.aspose.slides/presentationplayer) keret lekérése.

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
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
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

**Visszatér:**
[IImage](../../com.aspose.slides/iimage)