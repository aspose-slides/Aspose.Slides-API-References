---
title: HandoutLayoutingOptions
second_title: Aspose.Slides for Java API リファレンス
description: エクスポート用のハンドアウトプレゼンテーションレイアウトモードを表します。
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

エクスポート用のハンドアウトプレゼンテーションレイアウトモードを表します。

## コンストラクター

| Constructor | Description |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | デフォルト値を初期化します。 |

## メソッド

| Method | Description |
| --- | --- |
| [getHandout()](#getHandout--) | ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライドの数と順序を指定します。 |
| [setHandout(int value)](#setHandout-int-) | ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライドの数と順序を指定します。 |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | 表示されたスライド番号を印刷するかどうかを指定します。 |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | 表示されたスライド番号を印刷するかどうかを指定します。 |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | 表示されたスライドの周囲にフレームを描画するかどうかを指定します。 |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | 表示されたスライドの周囲にフレームを描画するかどうかを指定します。 |
| [getPrintComments()](#getPrintComments--) | スライド上のコメントを表示するかどうかを指定します。 |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | スライド上のコメントを表示するかどうかを指定します。 |

### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

デフォルト値を初期化します。

### getHandout() {#getHandout--}
```
public final int getHandout()
```

ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライドの数と順序を指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **HandoutType.Handouts6Horizontal** です。

**戻り値:**
int

### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

ページ [HandoutType](../../com.aspose.slides/handouttype) に配置されるスライドの数と順序を指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **HandoutType.Handouts6Horizontal** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

表示されたスライド番号を印刷するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **true** です。

**戻り値:**
boolean

### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

表示されたスライド番号を印刷するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **true** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

表示されたスライドの周囲にフレームを描画するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **true** です。

**戻り値:**
boolean

### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

表示されたスライドの周囲にフレームを描画するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **true** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

スライド上のコメントを表示するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **false** です。

**戻り値:**
boolean

### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

スライド上のコメントを表示するかどうかを指定します。

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

デフォルト値は  **false** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |