---
title: ITiffOptions
second_title: Aspose.Sildes for Java API Reference
description: p
 Provides options that control how a presentation is saved in TIFF format.
type: docs
weight: 1078
url: /java/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in TIFF format.
## Methods

| Method | Description |
| --- | --- |
| [getImageSize()](#getImageSize--) | Specifies size of a generated TIFF image. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Specifies size of a generated TIFF image. |
| [getDpiX()](#getDpiX--) | Specifies the horizontal resolution in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specifies the horizontal resolution in dots per inch. |
| [getDpiY()](#getDpiY--) | Specifies the vertical resolution in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specifies the vertical resolution in dots per inch. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getCompressionType()](#getCompressionType--) | Specifies the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifies the compression type. |
| [getPixelFormat()](#getPixelFormat--) | Specifies the pixel format for the generated images. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifies the pixel format for the generated images. |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension.

**Returns:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public abstract INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
