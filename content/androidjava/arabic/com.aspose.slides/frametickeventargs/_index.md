---
title: FrameTickEventArgs
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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

## الطرق

| الدالة | الوصف |
| --- | --- |
| [getPlayer()](#getPlayer--) | احصل على مشغل العرض |
| [getFrame()](#getFrame--) | احصل على الإطار الحالي [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
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

احصل على الإطار الحالي [PresentationPlayer](../../com.aspose.slides/presentationplayer).

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


**الإرجاع:**
[IImage](../../com.aspose.slides/iimage)