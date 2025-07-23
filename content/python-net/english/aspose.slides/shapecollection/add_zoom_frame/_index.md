---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---


## add_zoom_frame {#float-float-float-float-islide}
Creates a new Zoom frame and adds it to the end of the shape collection.

### Returns

The newly created [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The [`ISlide`](/slides/python-net/aspose.slides/islide) referenced by the Zoom frame;<br/><br/>            must belong to this presentation. |

### Examples

This example demonstrates adding a Zoom object to the end of a collection
            (assume that there are at least two slides in the "Presentation.pptx" presentation):

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced slide does not belong to the current presentation. |


## add_zoom_frame {#float-float-float-float-islide-ippimage}
Creates a new Zoom frame and adds it to the end of the shape collection.

### Returns

The newly created [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The [`ISlide`](/slides/python-net/aspose.slides/islide) referenced by the Zoom frame;<br/><br/>            must belong to this presentation. |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image for the referenced slide [`IPPImage`](/slides/python-net/aspose.slides/ippimage). |

### Examples

This example demonstrates adding a Zoom object to the end of a collection
            (assume that there are at least two slides in the "Presentation.pptx" presentation):

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced slide does not belong to the current presentation. |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

