---
title: FrameTickEventArgs
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل وسائط حدث PresentationPlayer.FrameTick.
type: docs
url: /ar/com.aspose.slides/frametickeventargs/
---
**الوراثة:**
java.lang.Object
```
public class FrameTickEventArgs
```

يمثل وسائط حدث PresentationPlayer.FrameTick.

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

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPlayer()](#getPlayer--) | احصل على مشغل العرض |
| [getFrame()](#getFrame--) | احصل على الإطار [PresentationPlayer](../../com.aspose.slides/presentationplayer) الحالي. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

احصل على مشغل العرض

**الإرجاع:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

احصل على الإطار [PresentationPlayer](../../com.aspose.slides/presentationplayer) الحالي.

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


**الإرجاع:**
[IImage](../../com.aspose.slides/iimage)