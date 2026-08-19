---
title: FrameTickEventArgs
second_title: Aspose.Slides برای مرجع API جاوا
description: آرگومان‌های رخداد PresentationPlayer.FrameTick را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/frametickeventargs/
---
**ارث‌بری:**
java.lang.Object
```
public class FrameTickEventArgs
```

آرگومان‌های رخداد PresentationPlayer.FrameTick را نشان می‌دهد.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getPlayer()](#getPlayer--) | پخش‌کننده ارائه را دریافت کنید |
| [getFrame()](#getFrame--) | فریم فعلی [PresentationPlayer](../../com.aspose.slides/presentationplayer) را دریافت کنید |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


پخش‌کننده ارائه را دریافت کنید

**بازگشت:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


فریم فعلی [PresentationPlayer](../../com.aspose.slides/presentationplayer) را دریافت کنید.

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

**بازگشت:**
[IImage](../../com.aspose.slides/iimage)