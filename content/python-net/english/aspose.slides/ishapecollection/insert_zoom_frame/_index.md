---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---


## insert_zoom_frame {#int-float-float-float-float-islide}
Creates a new Zoom object and inserts it to a collection at the specified index.

### Returns

Created Zoom object [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which Zoom frame should be inserted. |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The slide object referenced by the Zoom frame [`ISlide`](/slides/python-net/aspose.slides/islide). |

### Examples

This example demonstrates creation and inserting a Zoom object at the specified index of a collection
            (assume that there are at least two slides in the "Presentation.pptx" presentation):

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referenced slide does not belong to the current presentation. |


## insert_zoom_frame {#int-float-float-float-float-islide-ippimage}
Creates a new Zoom object and inserts it to a collection at the specified index.

### Returns

Created Zoom object [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which Zoom frame should be inserted. |
| x | **float** | X coordinate of a new Zoom frame **float**. |
| y | **float** | Y coordinate of a new Zoom frame **float**. |
| width | **float** | Width of a new Zoom frame **float**. |
| height | **float** | Height of a new Zoom frame **float**. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The slide object referenced by the Zoom frame [`ISlide`](/slides/python-net/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image for the referenced slide [`IPPImage`](/slides/python-net/aspose.slides/ippimage) |

### Examples

This example demonstrates creation and inserting a Zoom object at the specified index of a collection
            (assume that there are at least two slides in the "Presentation.pptx" presentation):

### Exceptions

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

