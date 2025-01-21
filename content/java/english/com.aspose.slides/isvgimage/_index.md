---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
url: /com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Represents an SVG image.
## Methods

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during SVG documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the SVG image as an EMF file. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Returns SVG content. Read-only String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Returns SVG data. Read-only byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Return callback interface used to resolve external resources during SVG documents import. Read-only [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Returns base URI of the specified SVG. Used to resolve relative links. Read-only String.

**Returns:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Saves the SVG image as an EMF file.

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
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

