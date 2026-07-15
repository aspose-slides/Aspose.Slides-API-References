---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: 表示動畫的播放者。
type: docs
url: /zh-hant/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

表示動畫的播放者。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      {
>          animationsGenerator.setNewAnimation(new PresentationAnimationsGenerator.NewAnimation() {
>              public void invoke(IPresentationAnimationPlayer animationPlayer) {
>                  System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>                  animationPlayer.setTimePosition(0);
>                  animationPlayer.getFrame().save("firstFrame.png");
> 
>                  animationPlayer.setTimePosition(animationPlayer.getDuration());
>                  animationPlayer.getFrame().save("lastFrame.png");
>          }});
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

由 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 透過其 PresentationAnimationsGenerator.NewAnimation 事件產生的動畫。

## Methods

| 方法 | 描述 |
| --- | --- |
| [getDuration()](#getDuration--) | 取得動畫持續時間（毫秒） |
| [setTimePosition(double time)](#setTimePosition-double-) | 設定動畫在  Duration（\#getDuration.getDuration）中的時間位置。 |
| [getFrame()](#getFrame--) | 取得先前以 \#setTimePosition(double).setTimePosition(double) 方法設定的目前時間位置之畫格。 |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


取得動畫持續時間（毫秒）

**返回:**  
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


設定動畫在  Duration（\#getDuration.getDuration）中的時間位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| time | double | 時間位置。 |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


取得先前以 \#setTimePosition(double).setTimePosition(double) 方法設定的目前時間位置之畫格。

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 框架圖像