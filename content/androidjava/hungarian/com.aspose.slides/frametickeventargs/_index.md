---
title: FrameTickEventArgs
second_title: Aspose.Slides Android számára Java API hivatkozás
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
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
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

| Method | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | Lekéri a prezentáció lejátszót |
| [getFrame()](#getFrame--) | Lekéri a jelenlegi [PresentationPlayer](../../com.aspose.slides/presentationplayer) keretet. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Lekéri a prezentáció lejátszót

**Visszatér:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Lekéri a jelenlegi [PresentationPlayer](../../com.aspose.slides/presentationplayer) keretet.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
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