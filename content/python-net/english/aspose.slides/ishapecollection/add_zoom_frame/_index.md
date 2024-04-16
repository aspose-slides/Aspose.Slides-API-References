---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---


## add_zoom_frame {#float-float-float-float-islide}
Adds a new Zoom object to the end of a collection.

### Returns

Created Zoom object [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The slide object referenced by the Zoom frame [`ISlide`](/slides/python-net/aspose.slides/islide). |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referenced slide does not belong to the current presentation. |


## add_zoom_frame {#float-float-float-float-islide-ippimage}
Adds a new Zoom object to the end of a collection.

### Returns

Created Zoom object [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The slide object referenced by the Zoom frame [`ISlide`](/slides/python-net/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image for the referenced slide [`IPPImage`](/slides/python-net/aspose.slides/ippimage) |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referenced slide does not belong to the current presentation. |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

