---
title: PresentationPlayer
second_title: Aspose.Slides for Java API 参考
description: 表示与 . 关联的动画播放器。
type: docs
url: /zh/com.aspose.slides/presentationplayer/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
com.aspose.ms.System.IDisposable  
```
public class PresentationPlayer implements System.IDisposable
```

表示与 [Presentation](../../com.aspose.slides/presentation) 关联的动画播放器。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // 以 33 FPS 播放动画
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
>          // 以 45 FPS 播放动画
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

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | 创建 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 释放 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 的实例。 |
| [getFrameIndex()](#getFrameIndex--) | 获取帧索引。 |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | 设置新的帧滴事件。 |

### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

创建 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | 演示文稿动画生成器 |
| fps | double | 每秒帧数（FPS） |

### dispose() {#dispose--}
```
public final void dispose()
```

释放 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 的实例。

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

获取帧索引。

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


**返回值:**
int

### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

设置新的帧滴事件。

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

当由 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 创建的动画的每一帧由播放器生成时触发。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | 帧滴事件。 |