---
title: SvgImage
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 表示 SVG 圖像。
type: docs
url: /zh-hant/com.aspose.slides/svgimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

表示 SVG 圖像。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | 建立新的 SvgImage 物件。 |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | 建立新的 SvgImage 物件。 |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | 建立新的 SvgImage 物件。 |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 建立新的 SvgImage 物件。 |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 建立新的 SvgImage 物件。 |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 建立新的 SvgImage 物件。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSvgData()](#getSvgData--) | 傳回 SVG 資料。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | 傳回用於在 Svg 文件匯入期間解析外部資源的回呼介面。 |
| [getBaseUri()](#getBaseUri--) | 傳回指定 Svg 的基礎 URI。 |
| [getSvgContent()](#getSvgContent--) | 傳回 SVG 內容。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 將 SVG 圖像儲存為 EMF 檔案。 |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | Svg 資料。 |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 內容。 |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 串流。 |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | Svg 資料。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| baseUri | java.lang.String | 指定 Svg 的基礎 URI。用於解析相對連結。 |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 內容。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| baseUri | java.lang.String | 指定 Svg 的基礎 URI。用於解析相對連結。 |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

建立新的 SvgImage 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 串流。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| baseUri | java.lang.String | 指定 Svg 的基礎 URI。用於解析相對連結。 |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

傳回 SVG 資料。唯讀 byte[]。

**傳回值：**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

傳回用於在 Svg 文件匯入期間解析外部資源的回呼介面。唯讀 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)。

**傳回值：**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

傳回指定 Svg 的基礎 URI。用於解析相對連結。唯讀 String。

**傳回值：**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

傳回 SVG 內容。唯讀 String。

**傳回值：**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

將 SVG 圖像儲存為 EMF 檔案。

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // 建立新的 SVG 圖像
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // 將 SVG 圖像儲存為 metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 建立新的 SVG 圖像
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // 將 SVG 圖像儲存為 metafille
>      svgImage.writeAsEmf(byteStream);
>      // 將 metafile 加入影像集合
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |