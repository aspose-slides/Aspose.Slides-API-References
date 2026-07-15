---
title: IGifOptions
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 GIF 匯出選項。
type: docs
url: /zh-hant/com.aspose.slides/igifoptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

表示 GIF 匯出選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 取得或設定影格大小。 |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | 取得或設定影格大小。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 判斷是否會匯出隱藏投影片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 判斷是否會匯出隱藏投影片。 |
| [getTransitionFps()](#getTransitionFps--) | 取得或設定過渡 FPS [frames/sec]，預設值為 25。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 取得或設定過渡 FPS [frames/sec]，預設值為 25。 |
| [getDefaultDelay()](#getDefaultDelay--) | 取得或設定預設延遲時間 [ms]。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 取得或設定預設延遲時間 [ms]。 |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


取得或設定影格大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**返回值：**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


取得或設定影格大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


判斷是否會匯出隱藏投影片。預設值為 false。

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


**返回值：**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


判斷是否會匯出隱藏投影片。預設值為 false。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


取得或設定過渡 FPS [frames/sec]，預設值為 25。

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

**返回值：**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


取得或設定過渡 FPS [frames/sec]，預設值為 25。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


取得或設定預設延遲時間 [ms]。如果未設定 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，將使用此值。預設值為 1000。

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


**返回值：**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


取得或設定預設延遲時間 [ms]。如果未設定 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，將使用此值。預設值為 1000。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |