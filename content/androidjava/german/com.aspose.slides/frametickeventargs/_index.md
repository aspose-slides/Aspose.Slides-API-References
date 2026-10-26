---
title: FrameTickEventArgs
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt die Argumente des PresentationPlayer.FrameTick-Ereignisses dar.
type: docs
url: /de/com.aspose.slides/frametickeventargs/
---
**Vererbung:**
java.lang.Object
```
public class FrameTickEventArgs
```

Stellt die Argumente des Ereignisses PresentationPlayer.FrameTick dar.

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

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPlayer()](#getPlayer--) | Gibt den Präsentationsplayer zurück |
| [getFrame()](#getFrame--) | Gibt den aktuellen [PresentationPlayer](../../com.aspose.slides/presentationplayer) Frame zurück |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Gibt den Präsentationsplayer zurück

**Rückgabewert:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Gibt den aktuellen [PresentationPlayer](../../com.aspose.slides/presentationplayer) Frame zurück.

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


**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage)