---
title: HtmlOptions
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: HTML エクスポート オプションを表します。
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

HTML エクスポート オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | コールバックを指定して新しい HtmlOptions オブジェクトを作成します。 |
| [HtmlOptions()](#HtmlOptions--) | 単一の HTML ファイルに保存するための新しい HtmlOptions オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML テンプレートを取得または設定します。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML テンプレートを取得または設定します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得または設定します。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | スライド画像形式のオプションを取得または設定します。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | スライド画像形式のオプションを取得または設定します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像の圧縮レベルを表します |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像の圧縮レベルを表します |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 切り取られた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 切り取られた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | 幅と高さの属性を svg コンテナから除外するには true に設定します。これによりレイアウトがレスポンシブになります。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | 幅と高さの属性を svg コンテナから除外するには true に設定します。これによりレイアウトがレスポンシブになります。 |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

コールバックを指定して新しい HtmlOptions オブジェクトを作成します。

**パラメーター:**
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

プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 既定値は false です。

**戻り値:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 既定値は false です。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML テンプレートを取得または設定します。 読み書き可能 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**戻り値:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML テンプレートを取得または設定します。 読み書き可能 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得または設定します。 true に設定すると、レンダリング出力でリガチャが無効になります。 既定では、このプロパティは false に設定されています。

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

テキストがリガチャを使用せずにレンダリングされるかどうかを示す値を取得または設定します。 true に設定すると、レンダリング出力でリガチャが無効になります。 既定では、このプロパティは false に設定されています。

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


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

スライド画像形式のオプションを取得または設定します。 読み書き可能 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**戻り値:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

スライド画像形式のオプションを取得または設定します。 読み書き可能 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 読み書き可能な byte。

--------------------

このプロパティは、ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するために使用します。 値は 0 から 100 の範囲で、0 は最悪の品質で最大圧縮、100 は最高の品質で最小圧縮を意味します。

既定値は **95** です。

**戻り値:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 読み書き可能な byte。

--------------------

このプロパティは、ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するために使用します。 値は 0 から 100 の範囲で、0 は最悪の品質で最大圧縮、100 は最高の品質で最小圧縮を意味します。

既定値は **95** です。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

画像の圧縮レベルを表します

**戻り値:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

画像の圧縮レベルを表します

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

切り取られた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 true に設定すると切り取られた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルサイズが大きくなる可能性があります）。

**戻り値:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

切り取られた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 true に設定すると切り取られた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルサイズが大きくなる可能性があります）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

幅と高さの属性を svg コンテナから除外するには true に設定します。これによりレイアウトがレスポンシブになります。 false の場合は除外しません。 読み書き可能な boolean。

**戻り値:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

幅と高さの属性を svg コンテナから除外するには true に設定します。これによりレイアウトがレスポンシブになります。 false の場合は除外しません。 読み書き可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |