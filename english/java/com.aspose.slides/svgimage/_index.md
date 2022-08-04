---
title: SvgImage
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an SVG image.
type: docs
weight: 536
url: /java/com.aspose.slides/svgimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Represents an SVG image.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Creates new SvgImage object. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Creates new SvgImage object. |
| [SvgImage(System.IO.Stream stream)](#SvgImage-com.aspose.ms.System.IO.Stream-) |  |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(System.IO.Stream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-com.aspose.ms.System.IO.Stream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during Svg documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified Svg. |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | java.lang.String | Svg content. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Svg stream. |

### SvgImage(System.IO.Stream stream) {#SvgImage-com.aspose.ms.System.IO.Stream-}
```
 SvgImage(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | java.lang.String | Base URI of the specified Svg. Used to resolve relative links. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgContent | java.lang.String | Svg content. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | java.lang.String | Base URI of the specified Svg. Used to resolve relative links. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Creates new SvgImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Svg stream. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | java.lang.String | Base URI of the specified Svg. Used to resolve relative links. |

### SvgImage(System.IO.Stream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-com.aspose.ms.System.IO.Stream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
 SvgImage(System.IO.Stream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) |  |
| baseUri | java.lang.String |  |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Returns SVG data. Read-only byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Return callback interface used to resolve external resources during Svg documents import. Read-only [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Returns base URI of the specified Svg. Used to resolve relative links. Read-only String.

**Returns:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Returns SVG content. Read-only String.

**Returns:**
java.lang.String
