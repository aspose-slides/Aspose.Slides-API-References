---
title: ImageCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/imagecollection/
---

## ImageCollection class

 Represents collection of PPImage.
 
### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([PPImage](../ppimage)) | Adds a copy of an image from an another presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| imageSource | [PPImage](../ppimage) | Source image. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (BufferedImage) | Add an image to a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| image | BufferedImage | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([IImage](../iimage)) | Add an image to a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| image | [IImage](../iimage) | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (InputStream) | Add an image to a presentation from stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image from. This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (InputStream, int) | Creates and adds an image to a presentation from stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (byte[]) | Adds an image to a presentation from specified buffer. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

 **Returns:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([SvgImage](../svgimage)) | Add an image to a presentation from Svg object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Svg image object ISvgImage |

 **Returns:**
[PPImage](../ppimage)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only IPPImage. |

 **Returns:**
[PPImage](../ppimage)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns a number of images in the collection. Read-only int. |

 **Returns:**
int


---


