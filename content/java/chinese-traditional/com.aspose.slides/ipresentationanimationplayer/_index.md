---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API 參考
description: 表示動畫的播放器。
type: docs
url: /zh-hant/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

表示動畫的播放器。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      {
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>              animationPlayer.setTimePosition(0);
>              animationPlayer.getFrame().save("firstFrame.png");
> 
>              animationPlayer.setTimePosition(animationPlayer.getDuration());
>              animationPlayer.getFrame().save("lastFrame.png");
>          });
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

動畫由 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 透過其 PresentationAnimationsGenerator.NewAnimation 事件產生。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getDuration()](#getDuration--) | 取得動畫持續時間 [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | 設定動畫時間位置於 Duration 內（\#getDuration.getDuration）。 |
| [getFrame()](#getFrame--) | 取得先前使用 \#setTimePosition(double).setTimePosition(double) 方法設定之目前時間位置的框架。 |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

取得動畫持續時間 [ms]

**傳回:**  
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

設定動畫時間位置於 Duration 內（\#getDuration.getDuration）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| time | double | 時間位置。 |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

取得先前使用 \#setTimePosition(double).setTimePosition(double) 方法設定之目前時間位置的框架。

**傳回:**
[IImage](../../com.aspose.slides/iimage) - 框架圖像