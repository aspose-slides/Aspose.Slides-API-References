---
title: ImageCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/imagecollection/
---

## ImageCollection class

 Represents collection of PPImage.
 
| [addImage] ([PPImage]) Adds a copy of an image from an another presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSource | [PPImage] | Source image. |

### Result
[PPImage]


---


| [addImage] ([BufferedImage]) Add an image to a presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| image | [BufferedImage] | Image to add. This function converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

### Result
[PPImage]


---


| [addImageFromStream ] (ImageCollection, [ReadStream], Function) Add an image to a presentation from stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imagecollection | ImageCollection  | link to self |
| stream | [ReadStream] | Stream to add image from. This function can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PPImage]


---


| [addImageFromStream ] (ImageCollection, [ReadStream], [int], Function) Creates and adds an image to a presentation from stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imagecollection | ImageCollection  | link to self |
| stream | [ReadStream] | Stream to add image file from. |
| loadingStreamBehavior | [int] | The behavior which will be applied to the stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PPImage]


---


| [addImage] ([byte[]]) Adds an image to a presentation from specified buffer. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| buffer | [byte[]] | Buffer. |

### Result
[PPImage]


---


| [addImage] ([SvgImage]) Add an image to a presentation from Svg object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage] | Svg image object ISvgImage |

### Result
[PPImage]

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


| [getSyncRoot] () Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) Gets the element at the specified index. Read-only IPPImage. |

### Result
[PPImage]


---


| [isSynchronized] () Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [size] () Returns a number of images in the collection. Read-only int. |

### Result
int


---


