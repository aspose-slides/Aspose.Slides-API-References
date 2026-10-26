---
title: IGifOptions
second_title: Java API リファレンスによる Aspose.Slides for Android
description: GIF エクスポートオプションを表します。
type: docs
url: /ja/com.aspose.slides/igifoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

GIF エクスポートオプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | フレーム サイズを取得または設定します。 |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | フレーム サイズを取得または設定します。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [getTransitionFps()](#getTransitionFps--) | 遷移 FPS [frames/sec] を取得または設定します。デフォルト値は 25 です。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 遷移 FPS [frames/sec] を取得または設定します。デフォルト値は 25 です。 |
| [getDefaultDelay()](#getDefaultDelay--) | デフォルト遅延時間 [ms] を取得または設定します。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | デフォルト遅延時間 [ms] を取得または設定します。 |

### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

フレーム サイズを取得または設定します。

--------------------

サイズが空の場合、値は [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) から取得されます。

**戻り値:**
[Size](../../com.aspose.slides.android/size)

### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

フレーム サイズを取得または設定します。

--------------------

サイズが空の場合、値は [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) から取得されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

非表示スライドがエクスポートされるかどうかを決定します。デフォルト値は false です。

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

**戻り値:**
boolean

### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

非表示スライドがエクスポートされるかどうかを決定します。デフォルト値は false です。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

遷移 FPS [frames/sec] を取得または設定します。デフォルト値は 25 です。

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

**戻り値:**
int

### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

遷移 FPS [frames/sec] を取得または設定します。デフォルト値は 25 です。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

デフォルト遅延時間 [ms] を取得または設定します。[ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) が設定されていない場合にこの値が使用されます。デフォルト値は 1000 です。

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

**戻り値:**
int

### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

デフォルト遅延時間 [ms] を取得または設定します。[ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) が設定されていない場合にこの値が使用されます。デフォルト値は 1000 です。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |