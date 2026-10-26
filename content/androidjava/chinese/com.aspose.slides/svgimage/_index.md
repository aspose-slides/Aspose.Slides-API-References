---
title: SvgImage
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 SVG 图像。
type: docs
url: /zh/com.aspose.slides/svgimage/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

表示一个 SVG 图像。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | 创建新的 SvgImage 对象。 |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | 创建新的 SvgImage 对象。 |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | 创建新的 SvgImage 对象。 |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 创建新的 SvgImage 对象。 |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 创建新的 SvgImage 对象。 |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 创建新的 SvgImage 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSvgData()](#getSvgData--) | 返回 SVG 数据。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | 返回在导入 Svg 文档期间用于解析外部资源的回调接口。 |
| [getBaseUri()](#getBaseUri--) | 返回指定 Svg 的基础 URI。 |
| [getSvgContent()](#getSvgContent--) | 返回 SVG 内容。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 将 SVG 图像保存为 EMF 文件。 |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Svg 数据。 |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 内容。 |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 流。 |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Svg 数据。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，所有外部对象将被忽略。 |
| baseUri | java.lang.String | 指定 Svg 的基础 URI。用于解析相对链接。 |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | java.lang.String | Svg 内容。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，所有外部对象将被忽略。 |
| baseUri | java.lang.String | 指定 Svg 的基础 URI。用于解析相对链接。 |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

创建新的 SvgImage 对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | Svg 流。 |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，所有外部对象将被忽略。 |
| baseUri | java.lang.String | 指定 Svg 的基础 URI。用于解析相对链接。 |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

返回 SVG 数据。只读 byte[]。

**返回值:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

返回在导入 Svg 文档期间用于解析外部资源的回调接口。只读 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)。

**返回值:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

返回指定 Svg 的基础 URI。用于解析相对链接。只读 String。

**返回值:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

返回 SVG 内容。只读 String。

**返回值:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

将 SVG 图像保存为 EMF 文件。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |