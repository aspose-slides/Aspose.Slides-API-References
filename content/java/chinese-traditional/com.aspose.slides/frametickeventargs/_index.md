---
title: FrameTickEventArgs
second_title: Aspose.Slides for Java API 參考
description: 表示 PresentationPlayer.FrameTick 事件的參數。
type: docs
url: /zh-hant/com.aspose.slides/frametickeventargs/
---
**繼承：**
java.lang.Object
```
public class FrameTickEventArgs
```

代表 PresentationPlayer.FrameTick 事件的參數。

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

| 方法 | 說明 |
| --- | --- |
| [getPlayer()](#getPlayer--) | 取得簡報播放器 |
| [getFrame()](#getFrame--) | 取得目前的 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 框架。 |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


取得簡報播放器

**返回值：**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


取得目前的 [PresentationPlayer](../../com.aspose.slides/presentationplayer) 框架。

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


**返回值：**
[IImage](../../com.aspose.slides/iimage)