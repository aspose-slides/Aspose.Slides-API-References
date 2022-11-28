---
title: TiffOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control how a presentation is saved in TIFF format.
type: docs
weight: 577
url: /java/com.aspose.slides/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Provides options that control how a presentation is saved in TIFF format.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getImageSize()](#getImageSize--) | Specifies size of a generated TIFF image. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Specifies size of a generated TIFF image. |
| [getDpiX()](#getDpiX--) | Specifies the horizontal resolution in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specifies the horizontal resolution in dots per inch. |
| [getDpiY()](#getDpiY--) | Specifies the vertical resolution in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specifies the vertical resolution in dots per inch. |
| [getCompressionType()](#getCompressionType--) | Specifies the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifies the compression type. |
| [getPixelFormat()](#getPixelFormat--) | Specifies the pixel format for the generated images. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifies the pixel format for the generated images. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Default constructor.

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public final INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension.

**Returns:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

