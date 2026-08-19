---
title: PresentationPlayer
second_title: Aspose.Slides for Java API Reference
description: نمایندهٔ پخش‌کنندهٔ انیمیشن‌های مرتبط با .
type: docs
url: /fa/com.aspose.slides/presentationplayer/
---
**وارثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

نمایندهٔ پخش‌کنندهٔ انیمیشن‌های مرتبط با [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // پخش انیمیشن با 33 فریم بر ثانیه
>          PresentationPlayer player33 = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player33.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("33fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player33 != null) player33.dispose();
>          }
>          // پخش انیمیشن با 45 فریم بر ثانیه
>          PresentationPlayer player45 = new PresentationPlayer(animationsGenerator, 45);
>          try {
>              player45.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("45fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player45 != null) player45.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | یک نمونهٔ جدید از [PresentationPlayer](../../com.aspose.slides/presentationplayer) ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [dispose()](#dispose--) | نمونهٔ [PresentationPlayer](../../com.aspose.slides/presentationplayer) را از بین می‌برد. |
| [getFrameIndex()](#getFrameIndex--) | شاخص فریم را دریافت می‌کند. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | یک رخداد تیک فریم جدید تنظیم می‌کند. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

یک نمونهٔ جدید از [PresentationPlayer](../../com.aspose.slides/presentationplayer) ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | ژنراتور انیمیشن‌های ارائه |
| fps | double | فریم‌ها بر ثانیه (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

نمونهٔ [PresentationPlayer](../../com.aspose.slides/presentationplayer) را از بین می‌برد.

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

شاخص فریم را دریافت می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
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
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

یک رخداد تیک فریم جدید تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
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

وقتی که هر فریم از انیمیشن ساخته‌شده توسط [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) توسط پخش‌کننده تولید می‌شود، رخ می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | رخداد تیک فریم. |