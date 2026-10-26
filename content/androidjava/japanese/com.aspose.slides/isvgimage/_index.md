---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: SVG 画像を表します。
type: docs
url: /ja/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

SVG 画像を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | SVG コンテンツを返します。 |
| [getSvgData()](#getSvgData--) | SVG データを返します。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスを返します。 |
| [getBaseUri()](#getBaseUri--) | 指定された SVG のベース URI を返します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG 画像を EMF ファイルとして保存します。 |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


SVG コンテンツを返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


SVG データを返します。読み取り専用 byte[]。

**戻り値:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


SVG ドキュメントのインポート中に外部リソースを解決するために使用されるコールバックインターフェイスを返します。読み取り専用 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)。

**戻り値:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


指定された SVG のベース URI を返します。相対リンクの解決に使用されます。読み取り専用 String。

**戻り値:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


SVG 画像を EMF ファイルとして保存します。

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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
>      // Saves the SVG image as a metafile
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲット ストリーム |