---
title: FrameTickEventArgs
second_title: Aspose.Slides for Android Java API Referansı
description: PresentationPlayer.FrameTick olayı için argümanları temsil eder.
type: docs
url: /tr/com.aspose.slides/frametickeventargs/
---
**Kalıtım:**
java.lang.Object
```
public class FrameTickEventArgs
```

PresentationPlayer.FrameTick olayının argümanlarını temsil eder.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPlayer()](#getPlayer--) | Sunum oynatıcısını al |
| [getFrame()](#getFrame--) | Geçerli [PresentationPlayer](../../com.aspose.slides/presentationplayer) çerçeveyi al. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Sunum oynatıcısını al

**Döndürür:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Geçerli [PresentationPlayer](../../com.aspose.slides/presentationplayer) çerçeveyi al.

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

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)