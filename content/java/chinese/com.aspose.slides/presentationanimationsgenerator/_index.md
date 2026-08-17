---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides for Java API 参考
description: 表示 动画的生成器。
type: docs
url: /zh/com.aspose.slides/presentationanimationsgenerator/
---
**继承：**
java.lang.Object

**所有实现的接口：**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

表示 [Presentation](../../com.aspose.slides/presentation) 中动画的生成器。

--------------------

> ```
> Presentation pres = new Presentation("animated.pptx");
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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | 创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。 |
| [PresentationAnimationsGenerator(Dimension frameSize)](#PresentationAnimationsGenerator-java.awt.Dimension-) | 创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。 |
| [PresentationAnimationsGenerator(Dimension2D frameSize)](#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-) | 创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 释放 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的实例。 |
| [getFrameSize()](#getFrameSize--) | 获取帧大小。 |
| [getDefaultDelay()](#getDefaultDelay--) | 获取或设置默认延迟时间（毫秒）。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 获取或设置默认延迟时间（毫秒）。 |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | 获取或设置是否应包括隐藏幻灯片。 |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | 获取或设置是否应包括隐藏幻灯片。 |
| [getExportedSlides()](#getExportedSlides--) | 获取已导出幻灯片的数量。 |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | 设置新的动画事件。 |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | 为每张幻灯片运行动画事件生成。 |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | 为每张幻灯片运行动画事件生成。 |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | 帧大小将根据 [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) 设置。 |
### PresentationAnimationsGenerator(Dimension frameSize) {#PresentationAnimationsGenerator-java.awt.Dimension-}
```
public PresentationAnimationsGenerator(Dimension frameSize)
```

创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameSize | java.awt.Dimension | 帧大小。 |
### PresentationAnimationsGenerator(Dimension2D frameSize) {#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-}
```
public PresentationAnimationsGenerator(Dimension2D frameSize)
```

创建 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameSize | java.awt.geom.Dimension2D | 帧大小。 |
### dispose() {#dispose--}
```
public final void dispose()
```

释放 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 的实例。

### getFrameSize() {#getFrameSize--}
```
public Dimension getFrameSize()
```

获取帧大小。

**返回值：**
java.awt.Dimension
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

获取或设置默认延迟时间（毫秒）。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1秒
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回值：**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

获取或设置默认延迟时间（毫秒）。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1秒
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

获取或设置是否应包括隐藏幻灯片。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回值：**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

获取或设置是否应包括隐藏幻灯片。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

获取已导出幻灯片的数量。

**返回值：**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

设置新的动画事件。

--------------------

> ```
> Presentation presentation = new Presentation("SimpleAnimations.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>          });
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | 动画事件。 |
### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

为每张幻灯片运行动画事件生成。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              animationsGenerator.setNewAnimation(animationPlayer ->
>              {
>                  // 处理新动画
>              });
>              player.setFrameTick((sender, args) ->
>              {
>                  // 处理新动画中的帧计时
>              });
>              animationsGenerator.run(presentation.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISSlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

为每张幻灯片运行动画事件生成。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.run(presentation.getSlides(), 33, (player, playerArgs) ->
>          {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>          });
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |