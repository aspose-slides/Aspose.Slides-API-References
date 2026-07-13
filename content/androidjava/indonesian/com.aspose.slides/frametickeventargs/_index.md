---
title: FrameTickEventArgs
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili argumen dari peristiwa PresentationPlayer.FrameTick.
type: docs
url: /id/com.aspose.slides/frametickeventargs/
---
**Pewarisan:**
java.lang.Object
```
public class FrameTickEventArgs
```

Mewakili argumen dari peristiwa PresentationPlayer.FrameTick.

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
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPlayer()](#getPlayer--) | Mendapatkan pemutar presentasi |
| [getFrame()](#getFrame--) | Mendapatkan frame [PresentationPlayer](../../com.aspose.slides/presentationplayer) saat ini. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

Mendapatkan pemutar presentasi

**Mengembalikan:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

Mendapatkan frame [PresentationPlayer](../../com.aspose.slides/presentationplayer) saat ini.

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

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage)