---
title: IImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a raster or vector image.
type: docs
url: /com.aspose.slides/iimage/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Represents a raster or vector image.

--------------------

This interface provides a common abstraction for handling both raster and vector images. Implementations may vary depending on the underlying image type.
## Methods

| Method | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Saves the image to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The path to the file where the image will be saved. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Saves the image to a file in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The path to the file where the image will be saved. |
| format | int | The image format. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Saves the image to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream where the image will be saved. |
| format | int | The image format. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


Saves the image to a file in the specified format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The path to the file where the image will be saved. |
| format | int | The image format. |
| quality | int | The quality of the saved image (0 to 100). This parameter only affects saving in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); for all other formats, it is ignored. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


Saves the image to a stream in the specified format and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream where the image will be saved. |
| format | int | The image format. |
| quality | int | The quality of the saved image (0 to 100). This parameter only affects saving in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); for all other formats, it is ignored. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


Gets the size of the image.

**Returns:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gets the width of the image in pixels.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gets the height of the image in pixels.

**Returns:**
int
