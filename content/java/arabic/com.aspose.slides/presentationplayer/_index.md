---
title: PresentationPlayer
second_title: مرجع API لـ Aspose.Slides لل Java
description: يمثل مشغل الرسوم المتحركة المرتبط بـ .
type: docs
url: /ar/com.aspose.slides/presentationplayer/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

يمثل مشغل الرسوم المتحركة المرتبط بـ [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // تشغيل الرسوم المتحركة بمعدل 33 إطارًا في الثانية
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
>          // تشغيل الرسوم المتحركة بمعدل 45 إطارًا في الثانية
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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | ينشئ نسخة جديدة من الـ [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | يقوم بتحرير نسخة الـ [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | يحصل على فهرس الإطار. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | يضبط حدث نبضة الإطار الجديد. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

ينشئ نسخة جديدة من الـ [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | مولّد الرسوم المتحركة للعرض |
| fps | double | الإطارات في الثانية (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

يقوم بتحرير نسخة الـ [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

يحصل على فهرس الإطار.

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

يضبط حدث نبضة الإطار الجديد.

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

--------------------

يحدث عندما يتم إنشاء كل إطار من الرسوم المتحركة التي أنشأها [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) بواسطة المشغل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | حدث نبضة الإطار. |