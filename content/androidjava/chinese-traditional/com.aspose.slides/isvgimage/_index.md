---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /zh-hant/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

表示 SVG 圖像。
## 方法

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | 返回 SVG 內容。 |
| [getSvgData()](#getSvgData--) | 返回 SVG 資料。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | 返回在 SVG 文件匯入期間用於解析外部資源的回呼介面。 |
| [getBaseUri()](#getBaseUri--) | 返回指定 SVG 的基礎 URI。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 將 SVG 圖像儲存為 EMF 檔案。 |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


返回 SVG 內容。唯讀 String.

**返回:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


返回 SVG 資料。唯讀 byte[].

**返回:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


返回在 SVG 文件匯入期間用於解析外部資源的回呼介面。唯讀 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**返回:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


返回指定 SVG 的基礎 URI。用於解析相對連結。唯讀 String.

**返回:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


將 SVG 圖像儲存為 EMF 檔案。

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

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標流 |