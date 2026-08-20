---
title: ImageCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของ PPImage.
type: docs
url: /th/com.aspose.slides/imagecollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทุกอินเทอร์เฟซที่ทำการ Implement:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Represents collection of PPImage.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | Returns a number of images in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adds a copy of an image from an another presentation. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Add an image to a presentation. |
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

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Gets the element at the specified index. Read-only [IPPImage](../../com.aspose.slides/ippimage).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Adds a copy of an image from an another presentation.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Source image. |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Add an image to a presentation.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Image to add.

--------------------

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Add an image to a presentation from stream.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add image from.

--------------------

This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Creates and adds an image to a presentation from stream.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Adds an image to a presentation from specified buffer.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Add an image to a presentation from Svg object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg image object [ISvgImage](../../com.aspose.slides/isvgimage) |

**ผลลัพธ์:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Returns an enumerator that iterates through the collection.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Returns a java iterator for the entire collection.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only  boolean .

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only  Object .

**ผลลัพธ์:**
java.lang.Object