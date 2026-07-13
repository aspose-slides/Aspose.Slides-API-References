---
title: FrameTickEventArgs
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje argumenty zdarzenia PresentationPlayer.FrameTick.
type: docs
url: /pl/com.aspose.slides/frametickeventargs/
---
**Dziedziczenie:**
java.lang.Object
```
public class FrameTickEventArgs
```

Reprezentuje argumenty zdarzenia PresentationPlayer.FrameTick.

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

## Metody

| Metoda | Opis |
| --- | --- |
| [getPlayer()](#getPlayer--) | Pobiera odtwarzacz prezentacji |
| [getFrame()](#getFrame--) | Pobiera bieżącą ramkę [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Pobiera odtwarzacz prezentacji

**Zwraca:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Pobiera bieżącą ramkę [PresentationPlayer](../../com.aspose.slides/presentationplayer).

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


**Zwraca:**
[IImage](../../com.aspose.slides/iimage)