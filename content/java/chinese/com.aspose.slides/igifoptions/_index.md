---
title: IGifOptions
second_title: Aspose.Slides Java API 参考
description: 表示 GIF 导出选项。
type: docs
url: /zh/com.aspose.slides/igifoptions/
---
**所有已实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

表示 GIF 导出选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 获取或设置帧大小。 |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | 获取或设置帧大小。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 确定是否导出隐藏的幻灯片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 确定是否导出隐藏的幻灯片。 |
| [getTransitionFps()](#getTransitionFps--) | 获取或设置过渡 FPS [frames/sec] 默认值为 25。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 获取或设置过渡 FPS [frames/sec] 默认值为 25。 |
| [getDefaultDelay()](#getDefaultDelay--) | 获取或设置默认延迟时间 [ms]。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 获取或设置默认延迟时间 [ms]。 |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


获取或设置帧大小。

--------------------

如果大小为空，则该值将取自 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**返回值:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


获取或设置帧大小。

--------------------

如果大小为空，则该值将取自 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract int getTransitionFps()
```


获取或设置过渡 FPS [frames/sec] 默认值为 25。

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
public abstract void setTransitionFps(int value)
```


获取或设置过渡 FPS [frames/sec] 默认值为 25。

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
public abstract int getDefaultDelay()
```


获取或设置默认延迟时间 [ms]。如果未设置 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，则使用此值。默认值为 1000。

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
public abstract void setDefaultDelay(int value)
```


获取或设置默认延迟时间 [ms]。如果未设置 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，则使用此值。默认值为 1000。

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