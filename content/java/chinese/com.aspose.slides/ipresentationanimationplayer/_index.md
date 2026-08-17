---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API 参考
description: 表示动画的播放器。
type: docs
url: /zh/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

表示动画的播放器。

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

由 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 通过其 PresentationAnimationsGenerator.NewAnimation 事件生成的动画。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDuration()](#getDuration--) | 获取动画持续时间 [毫秒] |
| [setTimePosition(double time)](#setTimePosition-double-) | 在 Duration（\#getDuration.getDuration）范围内设置动画时间位置。 |
| [getFrame()](#getFrame--) | 获取先前使用 \#setTimePosition(double).setTimePosition(double) 方法设置的当前时间位置的帧。 |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

获取动画持续时间 [毫秒]

**返回：**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

在 Duration（\#getDuration.getDuration）范围内设置动画时间位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| time | double | 时间位置。 |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

获取先前使用 \#setTimePosition(double).setTimePosition(double) 方法设置的当前时间位置的帧。

**返回：**
[IImage](../../com.aspose.slides/iimage) - 帧图像