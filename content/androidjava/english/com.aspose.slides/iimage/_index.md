---
title: IImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the raster or vector image.
type: docs
url: /com.aspose.slides/iimage/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Represents the raster or vector image.
## Methods

| Method | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Save the image to the file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Save the image to the file. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Save the image to the stream. |
| [getSize()](#getSize--) | Gets an image size. |
| [getWidth()](#getWidth--) | Gets the width of the image. |
| [getHeight()](#getHeight--) | Gets the height of the image. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Save the image to the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String |  |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Save the image to the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String |  |
| format | int |  |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Save the image to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | int |  |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


Gets an image size.

**Returns:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gets the width of the image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gets the height of the image.

**Returns:**
int
