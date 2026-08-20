---
title: PresentationPlayer
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงผู้เล่นของแอนิเมชันที่เชื่อมโยงกับ .
type: docs
url: /th/com.aspose.slides/presentationplayer/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

แสดงถึงผู้เล่นของแอนิเมชันที่เชื่อมโยงกับ [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // เล่นแอนิเมชันด้วย 33 FPS
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
>          // เล่นแอนิเมชันด้วย 45 FPS
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

## ผู้สร้าง

| ผู้สร้าง | คำอธิบาย |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | Creates new instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [dispose()](#dispose--) | Disposes the instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | Gets the frame index. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | Set a new frame tick event. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```


Creates new instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | Presentation animations generator |
| fps | double | Frames per second (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Gets the frame index.

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


**ส่งคืน:**
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```


Set a new frame tick event.

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

เกิดขึ้นเมื่อแต่ละเฟรมของแอนิเมชันที่สร้างโดย [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) ถูกสร้างโดยผู้เล่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | Frame tick event. |