---
title: FrameTickEventArgs
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش‌دهنده آرگومان‌های رویداد PresentationPlayer.FrameTick.
type: docs
url: /fa/com.aspose.slides/frametickeventargs/
---
**ارث‌بری:**
java.lang.Object
```
public class FrameTickEventArgs
```

نمایش‌دهنده آرگومان‌های رویداد PresentationPlayer.FrameTick.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getPlayer()](#getPlayer--) | دریافت پخش‌کنندهٔ ارائه |
| [getFrame()](#getFrame--) | دریافت فریم فعلی [PresentationPlayer](../../com.aspose.slides/presentationplayer) |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


دریافت پخش‌کنندهٔ ارائه

**باز می‌گردد:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


دریافت فریم فعلی [PresentationPlayer](../../com.aspose.slides/presentationplayer)

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

**باز می‌گردد:**
[IImage](../../com.aspose.slides/iimage)