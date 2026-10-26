---
title: HtmlOptions
second_title: Aspose.Slides for Java API リファレンス
description: HTML エクスポートオプションを表します。
type: docs
url: /ja/com.aspose.slides/htmloptions/
---
**継承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML エクスポートオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | コールバックを指定して新しい HtmlOptions オブジェクトを作成します。 |
| [HtmlOptions()](#HtmlOptions--) | 単一の HTML ファイルに保存するための新しい HtmlOptions オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML テンプレートを取得または設定します。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML テンプレートを取得または設定します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストをリガチャを使用せずに描画するかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストをリガチャを使用せずに描画するかどうかを示す値を取得または設定します。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | スライド画像フォーマットのオプションを取得または設定します。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | スライド画像フォーマットのオプションを取得または設定します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像の圧縮レベルを表します。 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像の圧縮レベルを表します。 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 切り取られた部分をドキュメントの一部として残すかどうかを示すブールフラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 切り取られた部分をドキュメントの一部として残すかどうかを示すブールフラグです。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | svg コンテナから width と height 属性を除外してレイアウトをレスポンシブにします。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | svg コンテナから width と height 属性を除外してレイアウトをレスポンシブにします。 |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

コールバックを指定して新しい HtmlOptions オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | プロジェクトの保存を制御するコールバックオブジェクトです。 |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

単一の HTML ファイルに保存するための新しい HtmlOptions オブジェクトを作成します。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML テンプレートを取得または設定します。読み書き [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**戻り値:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML テンプレートを取得または設定します。読み書き [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

テキストをリガチャを使用せずに描画するかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力でリガチャが無効になります。既定では false が設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

テキストをリガチャを使用せずに描画するかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力でリガチャが無効になります。既定では false が設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

スライド画像フォーマットのオプションを取得または設定します。読み書き [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**戻り値:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

スライド画像フォーマットのオプションを取得または設定します。読み書き [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み書き byte。

--------------------

JPEG 画像を含むドキュメントにのみ影響します。

PDF 形式で保存するときにドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。値は 0 から 100 の範囲で、0 は最悪の品質で最大圧縮、100 は最高の品質で最小圧縮を意味します。

デフォルト値は **95** です。

**戻り値:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み書き byte。

--------------------

JPEG 画像を含むドキュメントにのみ影響します。

PDF 形式で保存するときにドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。値は 0 から 100 の範囲で、0 は最悪の品質で最大圧縮、100 は最高の品質で最小圧縮を意味します。

デフォルト値は **95** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

画像の圧縮レベルを表します。

**戻り値:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

画像の圧縮レベルを表します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

切り取られた部分をドキュメントの一部として残すかどうかを示すブールフラグです。true の場合は切り取られた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。

**戻り値:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

切り取られた部分をドキュメントの一部として残すかどうかを示すブールフラグです。true の場合は切り取られた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

svg コンテナから width と height 属性を除外してレイアウトをレスポンシブにします。除外しない場合は false となります。読み書き boolean。

**戻り値:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

svg コンテナから width と height 属性を除外してレイアウトをレスポンシブにします。除外しない場合は false となります。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |