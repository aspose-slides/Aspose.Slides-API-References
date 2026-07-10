---
title: GifOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 GIF 导出选项。
type: docs
url: /zh/com.aspose.slides/gifoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口：**
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
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // 生成的 GIF 的大小
>      gifOptions.setDefaultDelay(2000); // 每张幻灯片显示的时长，直至切换到下一张
>      gifOptions.setTransitionFps(35); // 提高 FPS 以获得更好的过渡动画质量
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initializes a new instance of the GifOptions class. |
## Methods

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Gets or sets frame size. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Gets or sets frame size. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determines whether hidden slides will be exported. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determines whether hidden slides will be exported. |
| [getTransitionFps()](#getTransitionFps--) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Gets or sets default delay time [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Gets or sets default delay time [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

初始化 GifOptions 类的新实例。

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

获取或设置帧大小。

--------------------

如果尺寸为空，则该值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**返回：**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

获取或设置帧大小。

--------------------

如果尺寸为空，则该值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

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

**返回：**
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

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

获取或设置过渡 FPS [frames/sec] 默认值为 25.

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

**返回：**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```
获取或设置过渡 FPS [frames/sec] 默认值为 25.

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

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

获取或设置默认延迟时间 [ms]。如果未设置 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，则使用此值。默认值为 1000.

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

**返回：**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)

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

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |