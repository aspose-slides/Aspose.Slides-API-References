---
title: GifOptions
second_title: Aspose.Slides Java API 参考
description: 表示 GIF 导出选项。
type: docs
url: /zh/com.aspose.slides/gifoptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

表示 GIF 导出选项。

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // 生成的 GIF 的大小
>      gifOptions.setDefaultDelay(2000); // 每张幻灯片显示的时长，直到切换到下一张
>      gifOptions.setTransitionFps(35); // 提高 FPS 以获得更好的过渡动画质量
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifOptions()](#GifOptions--) | 初始化 GifOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 获取或设置帧大小。 |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | 获取或设置帧大小。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 确定是否导出隐藏的幻灯片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 确定是否导出隐藏的幻灯片。 |
| [getTransitionFps()](#getTransitionFps--) | 获取或设置过渡帧率（FPS）[帧/秒]，默认值为 25。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 获取或设置过渡帧率（FPS）[帧/秒]，默认值为 25。 |
| [getDefaultDelay()](#getDefaultDelay--) | 获取或设置默认延迟时间 [毫秒]。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 获取或设置默认延迟时间 [毫秒]。 |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


初始化 GifOptions 类的新实例。

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


获取或设置帧大小。

--------------------

如果大小为空，则值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**返回值:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


获取或设置帧大小。

--------------------

如果大小为空，则值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


确定是否导出隐藏的幻灯片。默认值为 false。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


确定是否导出隐藏的幻灯片。默认值为 false。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


获取或设置过渡帧率（FPS）[帧/秒]，默认值为 25。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


获取或设置过渡帧率（FPS）[帧/秒]，默认值为 25。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


获取或设置默认延迟时间 [毫秒]。如果未设置 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，将使用此值。默认值为 1000。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


获取或设置默认延迟时间 [毫秒]。如果未设置 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，将使用此值。默认值为 1000。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |