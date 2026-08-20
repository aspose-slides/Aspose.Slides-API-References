---
title: IGifOptions
second_title: Aspose.Slides for Java API 參考
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
| [getFrameSize()](#getFrameSize--) | Gets or sets frame size. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Gets or sets frame size. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determines whether hidden slides will be exported. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determines whether hidden slides will be exported. |
| [getTransitionFps()](#getTransitionFps--) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Gets or sets default delay time [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Gets or sets default delay time [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


取得或設定影格大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**傳回：**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


取得或設定影格大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


判斷是否匯出隱藏投影片。預設值為 false。

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

**傳回：**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


判斷是否匯出隱藏投影片。預設值為 false。

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

**傳回：**
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

**傳回：**
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