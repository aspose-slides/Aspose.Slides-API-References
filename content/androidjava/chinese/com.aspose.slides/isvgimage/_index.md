---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /zh/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

表示一个 SVG 图像。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | 返回 SVG 内容。 |
| [getSvgData()](#getSvgData--) | 返回 SVG 数据。 |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | 返回用于在导入 SVG 文档期间解析外部资源的回调接口。 |
| [getBaseUri()](#getBaseUri--) | 返回指定 SVG 的基础 URI。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 将 SVG 图像保存为 EMF 文件。 |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

返回 SVG 内容。只读 String。

**返回值:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

返回 SVG 数据。只读 byte[]。

**返回值:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

返回用于在导入 SVG 文档期间解析外部资源的回调接口。只读 [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)。

**返回值:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

返回指定 SVG 的基础 URI。用于解析相对链接。只读 String。

**返回值:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

将 SVG 图像保存为 EMF 文件。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |