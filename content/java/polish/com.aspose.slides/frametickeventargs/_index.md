---
title: FrameTickEventArgs
second_title: Aspose.Slides dla Java – referencja API
description: Reprezentuje argumenty zdarzenia PresentationPlayer.FrameTick.
type: docs
url: /pl/com.aspose.slides/frametickeventargs/
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
## Metody

| Method | Description |
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

**Zwraca:**
[IImage](../../com.aspose.slides/iimage)