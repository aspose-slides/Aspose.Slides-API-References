---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
weight: 953
url: /androidjava/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Represents an image in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an image's data. |
| [getSystemImage()](#getSystemImage--) | Returns the copy of an image of the System.Drawing.Image type. |
| [getSvgImage()](#getSvgImage--) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Replaces image data. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Replaces image. |
| [getContentType()](#getContentType--) | Returns a MIME type of an image, encoded in (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Returns a width of an image. |
| [getHeight()](#getHeight--) | Returns a height of an image. |
| [getX()](#getX--) | Returns a X-offset of an image. |
| [getY()](#getY--) | Returns a Y-offset of an image. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returns the copy of an image's data. Read-only byte[].

**Returns:**
byte[]
### getSystemImage() {#getSystemImage--}
```
public abstract Bitmap getSystemImage()
```


Returns the copy of an image of the System.Drawing.Image type. Read-only android.graphics.Bitmap.

**Returns:**
android.graphics.Bitmap
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

This value indicates that this image has been created from SVG.

**Returns:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
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
public abstract void replaceImage(byte[] newImageData)
```


Replaces image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | The new image's data. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Replaces image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | The new IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Returns a MIME type of an image, encoded in (\#getBinaryData.getBinaryData). Read-only String.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Returns a width of an image. Read-only int.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Returns a height of an image. Read-only int.

**Returns:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Returns a X-offset of an image. Read-only int.

**Returns:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Returns a Y-offset of an image. Read-only int.

**Returns:**
int
