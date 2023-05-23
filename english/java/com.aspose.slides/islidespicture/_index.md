---
title: ISlidesPicture
second_title: Aspose.Slides for Java API Reference
description: Represents a picture in a presentation.
type: docs
weight: 1038
url: /java/com.aspose.slides/islidespicture/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Represents a picture in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Returns or sets the embedded image. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returns or sets the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns of sets linked image's URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns of sets linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Returns or sets the embedded image. Read/write [IPPImage](../../com.aspose.slides/ippimage).

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Returns or sets the embedded image. Read/write [IPPImage](../../com.aspose.slides/ippimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returns of sets linked image's URL. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returns of sets linked image's URL. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Returns the collection of image transform effects. Read-only [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Returns:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
