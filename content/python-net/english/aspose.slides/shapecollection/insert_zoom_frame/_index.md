---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---


## insert_zoom_frame {#int-float-float-float-float-islide}
Creates a new Zoom frame and inserts it into the shape collection at the specified index.

### Returns

The newly created [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Zoom frame. |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The [`ISlide`](/slides/python-net/aspose.slides/islide) referenced by the Zoom frame. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced slide does not belong to the current presentation. |


## insert_zoom_frame {#int-float-float-float-float-islide-ippimage}
Creates a new Zoom frame with a predefined image and inserts it into the shape collection
            at the specified index.

### Returns

The newly created [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Zoom frame. |
| x | **float** | The x-coordinate of the new Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Zoom frame, in points. |
| width | **float** | The width of the new Zoom frame, in points. |
| height | **float** | The height of the new Zoom frame, in points. |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | The [`ISlide`](/slides/python-net/aspose.slides/islide) referenced by the Zoom frame. |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image for the referenced slide [`IPPImage`](/slides/python-net/aspose.slides/ippimage). |

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

