---
title: ImageCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of PPImage.
type: docs
url: /com.aspose.slides/imagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Represents collection of PPImage.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of images in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adds a copy of an image from an another presentation. |
| [addImage(BufferedImage image)](#addImage-java.awt.image.BufferedImage-) | Add an image to a presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Add an image to a presentation from stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Creates and adds an image to a presentation from stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Add an image to a presentation from Svg object. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Returns a number of images in the collection. Read-only  int .

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Gets the element at the specified index. Read-only [IPPImage](../../com.aspose.slides/ippimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Adds a copy of an image from an another presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Source image. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(BufferedImage image) {#addImage-java.awt.image.BufferedImage-}
```
public final IPPImage addImage(BufferedImage image)
```


Add an image to a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Image to add.

--------------------

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Add an image to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add image from.

--------------------

This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Creates and adds an image to a presentation from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Adds an image to a presentation from specified buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Add an image to a presentation from Svg object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg image object [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only  Object .

**Returns:**
java.lang.Object
