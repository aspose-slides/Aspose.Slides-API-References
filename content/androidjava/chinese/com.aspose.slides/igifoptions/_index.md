---
title: IGifOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 GIF 导出选项。
type: docs
url: /zh/com.aspose.slides/igifoptions/
---
**所有实现的接口:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

表示 GIF 导出选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 获取或设置帧大小。 |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | 获取或设置帧大小。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 确定是否导出隐藏的幻灯片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 确定是否导出隐藏的幻灯片。 |
| [getTransitionFps()](#getTransitionFps--) | 获取或设置过渡 FPS [frames/sec]，默认值为 25。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 获取或设置过渡 FPS [frames/sec]，默认值为 25。 |
| [getDefaultDelay()](#getDefaultDelay--) | 获取或设置默认延迟时间 [ms]。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 获取或设置默认延迟时间 [ms]。 |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

获取或设置帧大小。

--------------------

如果大小为空，则该值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**返回:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

获取或设置帧大小。

--------------------

如果大小为空，则该值将从 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 获取。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
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

**Returns:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Determines whether hidden slides will be exported. The default value is false.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


Gets or sets transition FPS [frames/sec] The default value is 25.

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

**Returns:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Gets or sets transition FPS [frames/sec] The default value is 25.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


Gets or sets default delay time [ms]. This value will be used if [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) is not set. The default value is 1000.

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

**Returns:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)

Gets or sets default delay time [ms]. This value will be used if [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) is not set. The default value is 1000.

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