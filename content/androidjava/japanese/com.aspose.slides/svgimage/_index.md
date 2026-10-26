---
title: SvgImage
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: SVG 画像を表します。
type: docs
url: /ja/com.aspose.slides/svgimage/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

SVG 画像を表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | 新しい SvgImage オブジェクトを作成します。 |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | 新しい SvgImage オブジェクトを作成します。 |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | 新しい SvgImage オブジェクトを作成します。 |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 新しい SvgImage オブジェクトを作成します。 |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 新しい SvgImage オブジェクトを作成します。 |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 新しい SvgImage オブジェクトを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSvgData()](#getSvgData--) | SVG データを返します。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Svg ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスを返します。 |
| [getBaseUri()](#getBaseUri--) | 指定された Svg のベース URI を返します。 |
| [getSvgContent()](#getSvgContent--) | SVG コンテンツを返します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG 画像を EMF ファイルとして保存します。 |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | Svg データ。 |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg コンテンツ。 |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg ストリーム。 |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | Svg データ。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | java.lang.String | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg コンテンツ。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | java.lang.String | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

新しい SvgImage オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg ストリーム。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| baseUri | java.lang.String | 指定された Svg のベース URI。相対リンクの解決に使用されます。 |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

SVG データを返します。読み取り専用 byte[]。

**戻り値:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Svg ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスを返します。読み取り専用 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)。

**戻り値:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

指定された Svg のベース URI を返します。相対リンクの解決に使用されます。読み取り専用 String。

**戻り値:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

SVG コンテンツを返します。読み取り専用 String。

**戻り値:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

SVG 画像を EMF ファイルとして保存します。

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲット ストリーム |