---
title: IHtmlOptions
second_title: Aspose.Slides for Java API リファレンス
description: HTML エクスポート オプションを表します。
type: docs
url: /ja/com.aspose.slides/ihtmloptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

HTML エクスポート オプションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML テンプレートを取得または設定します。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML テンプレートを取得または設定します。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | スライド画像形式オプションを取得または設定します。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | スライド画像形式オプションを取得または設定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getPicturesCompression()](#getPicturesCompression--) | 画像圧縮レベルを表します。読み取り/書き込み [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 画像圧縮レベルを表します。読み取り/書き込み [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 切り抜かれた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 切り抜かれた部分がドキュメントの一部として残るかどうかを示すブールフラグです。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG コンテナーから幅と高さ属性を除外する場合は true を設定します。これによりレイアウトがレスポンシブになります。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG コンテナーから幅と高さ属性を除外する場合は true を設定します。これによりレイアウトがレスポンシブになります。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | リガチャを使用せずにテキストがレンダリングされるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | リガチャを使用せずにテキストがレンダリングされるかどうかを示す値を取得または設定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

HTML テンプレートを取得または設定します。読み取り/書き込み [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**戻り値:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

HTML テンプレートを取得または設定します。読み取り/書き込み [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |
### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

スライド画像形式オプションを取得または設定します。読み取り/書き込み [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**戻り値:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

スライド画像形式オプションを取得または設定します。読み取り/書き込み [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み取り/書き込み byte。

--------------------

JPEG 画像を含むドキュメントにのみ影響します。

このプロパティを使用して、PDF 形式で保存する際の画像品質を取得または設定します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **95** です。

**戻り値:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み取り/書き込み byte。

--------------------

JPEG 画像を含むドキュメントにのみ影響します。

このプロパティを使用して、PDF 形式で保存する際の画像品質を取得または設定します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **95** です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

画像圧縮レベルを表します。読み取り/書き込み [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**戻り値:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

画像圧縮レベルを表します。読み取り/書き込み [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

切り抜かれた部分がドキュメントの一部として残るかどうかを示すブールフラグです。true の場合は切り抜かれた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。読み取り/書き込み boolean。

**戻り値:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

切り抜かれた部分がドキュメントの一部として残るかどうかを示すブールフラグです。true の場合は切り抜かれた部分が削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

true を設定すると SVG コンテナーから幅と高さ属性が除外され、レイアウトがレスポンシブになります。false の場合は除外されません。読み取り/書き込み boolean。

**戻り値:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

true を設定すると SVG コンテナーから幅と高さ属性が除外され、レイアウトがレスポンシブになります。false の場合は除外されません。読み取り/書き込み boolean。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

リガチャを使用せずにテキストがレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力でリガチャが無効になります。既定では false です。

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
public abstract void setDisableFontLigatures(boolean value)
```

リガチャを使用せずにテキストがレンダリングされるかどうかを示す値を取得または設定します。true に設定すると、レンダリング出力でリガチャが無効になります。既定では false です。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

--------------------

> ```
> 例:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)