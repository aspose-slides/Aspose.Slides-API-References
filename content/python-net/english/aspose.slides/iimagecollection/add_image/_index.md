---
title: add_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iimagecollection/add_image/
weight: 10
---


## add_image {#asposepydrawingimage}
Add an image to a presentation.

### Returns

Added image.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image | **aspose.pydrawing.Image** | Image to add. |

### Remarks

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation.


## add_image {#iimage}
Add an image to a presentation.

### Returns

Added image.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/aspose.slides/iimage) | Image to add. |

### Remarks

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation.


## add_image {#iorawiobase}
Add an image to a presentation from stream.

### Returns

Added image.



```python
def add_image(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image from. |

### Remarks

This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image.


## add_image {#bytes}
Adds an image to a presentation from specified buffer.

### Returns

Added image.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image {#ippimage}
Adds a copy of an image from an another presentation.

### Returns

Added image.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | Source image. |


## add_image {#isvgimage}
Add an image to a presentation from SVG object.

### Returns

Added image.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) | SVG image object [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Thrown when svgImage parameter is null. |


## add_image {#iorawiobase-loadingstreambehavior}
Creates and adds an image to a presentation from stream.

### Returns

Added [`IPPImage`](/slides/python-net/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image file from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/aspose.slides/loadingstreambehavior) | The behavior which will be applied to the stream. |



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

