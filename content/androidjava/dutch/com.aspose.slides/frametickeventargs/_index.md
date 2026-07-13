---
title: FrameTickEventArgs
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de argumenten van het PresentationPlayer.FrameTick-evenement voor.
type: docs
url: /nl/com.aspose.slides/frametickeventargs/
---
**Overerving:**
java.lang.Object
```
public class FrameTickEventArgs
```

Stelt de argumenten van het PresentationPlayer.FrameTick-evenement voor.

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

| Methode | Beschrijving |
| --- | --- |
| [getPlayer()](#getPlayer--) | Haal de presentatie-speler op |
| [getFrame()](#getFrame--) | Haal het huidige [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame op. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Haal de presentatie-speler op

**Retour:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Haal het huidige [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame op.

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


**Retour:**
[IImage](../../com.aspose.slides/iimage)