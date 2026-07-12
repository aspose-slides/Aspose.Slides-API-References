---
title: HandoutLayoutingOptions
second_title: Java API リファレンスによる Aspose.Slides for Android
description: エクスポート用の配布資料プレゼンテーションレイアウトモードを表します。
type: docs
url: /ja/com.aspose.slides/handoutlayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Represents the handout presentation layout mode for export.
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | 初期値を設定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHandout()](#getHandout--) | ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライド数と順序を指定します。 |
| [setHandout(int value)](#setHandout-int-) | ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライド数と順序を指定します。 |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | 表示されるスライド番号を印刷するかどうかを指定します。 |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | 表示されるスライド番号を印刷するかどうかを指定します。 |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | 表示されるスライドの周囲にフレームを描画するかどうかを指定します。 |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | 表示されるスライドの周囲にフレームを描画するかどうかを指定します。 |
| [getPrintComments()](#getPrintComments--) | スライド上のコメントを表示するかどうかを指定します |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | スライド上のコメントを表示するかどうかを指定します |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


初期値を設定します。

### getHandout() {#getHandout--}
```
public final int getHandout()
```


ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライド数と順序を指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **HandoutType.Handouts6Horizontal** 。

**戻り値:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライド数と順序を指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **HandoutType.Handouts6Horizontal** 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


表示されるスライド番号を印刷するかどうかを指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **true** 。

**戻り値:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


表示されるスライド番号を印刷するかどうかを指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **true** 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


表示されるスライドの周囲にフレームを描画するかどうかを指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **true** 。

**戻り値:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


表示されるスライドの周囲にフレームを描画するかどうかを指定します。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **true** 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


スライド上のコメントを表示するかどうかを指定します

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **false** 。

**戻り値:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


スライド上のコメントを表示するかどうかを指定します

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は **false** 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |