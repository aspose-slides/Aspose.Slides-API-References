---
title: GifOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示 GIF 匯出選項。
type: docs
url: /zh-hant/com.aspose.slides/gifoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面：**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

表示 GIF 匯出選項。

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // 產生的 GIF 大小
>      gifOptions.setDefaultDelay(2000); // 每張投影片顯示的時間長度，直到切換到下一張
>      gifOptions.setTransitionFps(35); // 提高 FPS 以提升轉場動畫品質
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 建構子

| 建構函式 | 說明 |
| --- | --- |
| [GifOptions()](#GifOptions--) | 初始化 GifOptions 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | 取得或設定框架大小。 |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | 取得或設定框架大小。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 判斷是否匯出隱藏的投影片。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 判斷是否匯出隱藏的投影片。 |
| [getTransitionFps()](#getTransitionFps--) | 取得或設定轉場 FPS [frames/sec]。預設值為 25。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 取得或設定轉場 FPS [frames/sec]。預設值為 25。 |
| [getDefaultDelay()](#getDefaultDelay--) | 取得或設定預設延遲時間 [ms]。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | 取得或設定預設延遲時間 [ms]。 |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

初始化 GifOptions 類別的新執行個體。

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

取得或設定框架大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**傳回值：**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

取得或設定框架大小。

--------------------

如果大小為空，則會從 [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) 取得值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

判斷是否匯出隱藏的投影片。預設值為 false。

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


**傳回值：**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

判斷是否匯出隱藏的投影片。預設值為 false。

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
public final int getTransitionFps()
```

取得或設定轉場 FPS [frames/sec]。預設值為 25。

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


**傳回值：**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

取得或設定轉場 FPS [frames/sec]。預設值為 25。

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
public final int getDefaultDelay()
```

取得或設定預設延遲時間 [ms]。如果未設定 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，則會使用此值。預設值為 1000。

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


**傳回值：**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

取得或設定預設延遲時間 [ms]。如果未設定 [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-)，則會使用此值。預設值為 1000。

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