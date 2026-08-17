---
title: FrameTickEventArgs
second_title: Aspose.Slides for Java API 参考
description: 表示 PresentationPlayer.FrameTick 事件的参数。
type: docs
url: /zh/com.aspose.slides/frametickeventargs/
---
**继承：**
java.lang.Object
```
public class FrameTickEventArgs
```

表示 PresentationPlayer.FrameTick 事件的参数。

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

## 方法

| Method | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | 获取演示播放器 |
| [getFrame()](#getFrame--) | 获取当前 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 帧。 |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


获取演示播放器

**返回：**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


获取当前 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 帧。

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


**返回：**
[IImage](../../com.aspose.slides/iimage)