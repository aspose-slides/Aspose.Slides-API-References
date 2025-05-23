---
title: PPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /com.aspose.slides/ppimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Represents an image in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an image's data. |
| [getSystemImage()](#getSystemImage--) | Returns the copy of an image. |
| [getImage()](#getImage--) | Returns the copy of an image. |
| [getSvgImage()](#getSvgImage--) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Replaces image data. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Replaces image data. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Replaces image data. |
| [getContentType()](#getContentType--) | Returns a MIME type of an image, encoded in  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Returns a width of an image. |
| [getHeight()](#getHeight--) | Returns a height of an image. |
| [getX()](#getX--) | Returns a X-offset of an image. |
| [getY()](#getY--) | Returns a Y-offset of an image. |
| [hashCode()](#hashCode--) | Returns the hash code of an image. |
| [dispose()](#dispose--) | Disposes object. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returns the copy of an image's data. Read-only  byte[] .

**Returns:**
byte[] - Array of bytes
### getSystemImage() {#getSystemImage--}
```
public final BufferedImage getSystemImage()
```


Returns the copy of an image. Read-only java.awt.image.BufferedImage.

**Returns:**
java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public final IImage getImage()
```


Returns the copy of an image. Read-only [IImage](../../com.aspose.slides/iimage).

**Returns:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

This value indicates that this image has been created from SVG.

**Returns:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

This value indicates that this image has been created from SVG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Replaces image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | The new image's data. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Replaces image data. Attention: when Image is metafile - it will be rasterized. Use replaceImage(byte[]) instead

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | The new image. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Replaces image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | The new IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns a MIME type of an image, encoded in  BinaryData (\#getBinaryData.getBinaryData). Read-only String.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Returns a width of an image. Read-only  int .

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Returns a height of an image. Read-only  int .

**Returns:**
int
### getX() {#getX--}
```
public final int getX()
```


Returns a X-offset of an image. Read-only  int .

**Returns:**
int
### getY() {#getY--}
```
public final int getY()
```


Returns a Y-offset of an image. Read-only  int .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code of an image.

**Returns:**
int - Hash code.
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes object.

