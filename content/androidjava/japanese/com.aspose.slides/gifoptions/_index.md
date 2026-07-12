---
title: GifOptions
second_title: Java API リファレンスによる Aspose.Slides for Android
description: GIF エクスポート オプションを表します。
type: docs
url: /ja/com.aspose.slides/gifoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

GIF エクスポート オプションを表します。

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // 生成された GIF のサイズ
>      gifOptions.setDefaultDelay(2000); // 各スライドが次のスライドに切り替わるまでの表示時間
>      gifOptions.setTransitionFps(35); // 遷移アニメーションの品質向上のために FPS を上げる
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | フレームサイズを取得または設定します。 |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | フレームサイズを取得または設定します。 |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 非表示スライドがエクスポートされるかどうかを決定します。 |
| [getTransitionFps()](#getTransitionFps--) | 遷移 FPS（フレーム/秒）を取得または設定します。デフォルト値は 25 です。 |
| [setTransitionFps(int value)](#setTransitionFps-int-) | 遷移 FPS（フレーム/秒）を取得または設定します。デフォルト値は 25 です。 |
| [getDefaultDelay()](#getDefaultDelay--) | デフォルトの遅延時間（ミリ秒）を取得または設定します。 |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | デフォルトの遅延時間（ミリ秒）を取得または設定します。 |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions クラスの新しいインスタンスを初期化します。

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


フレームサイズを取得または設定します。

--------------------

サイズが空の場合、値は [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) から取得されます。

**戻り値:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


フレームサイズを取得または設定します。

--------------------

サイズが空の場合、値は [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) から取得されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


遷移 FPS（フレーム/秒）を取得または設定します。デフォルト値は 25 です。

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
public final void setTransitionFps(int value)
```


遷移 FPS（フレーム/秒）を取得または設定します。デフォルト値は 25 です。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


デフォルトの遅延時間（ミリ秒）を取得または設定します。この値は [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) が設定されていない場合に使用されます。デフォルト値は 1000 です。

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
public final void setDefaultDelay(int value)
```


デフォルトの遅延時間（ミリ秒）を取得または設定します。この値は [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) が設定されていない場合に使用されます。デフォルト値は 1000 です。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |