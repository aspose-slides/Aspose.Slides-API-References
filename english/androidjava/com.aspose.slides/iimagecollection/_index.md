---
title: IImageCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of PPImage.
type: docs
weight: 829
url: /java/com.aspose.slides/iimagecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Represents collection of PPImage.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns image by its index. |
| [addImage(Bitmap image)](#addImage-android.graphics.Bitmap-) | Add an image to a presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Add an image to a presentation from stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Creates and adds an image to a presentation from stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adds a copy of an image from an another presentation. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Add an image to a presentation from SVG object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Returns image by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(Bitmap image) {#addImage-android.graphics.Bitmap-}
```
public abstract IPPImage addImage(Bitmap image)
```


Add an image to a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | android.graphics.Bitmap | Image to add.

--------------------

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
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
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
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
public abstract IPPImage addImage(byte[] buffer)
```


Adds an image to a presentation from specified buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Adds a copy of an image from an another presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Source image. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Add an image to a presentation from SVG object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG image object [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
