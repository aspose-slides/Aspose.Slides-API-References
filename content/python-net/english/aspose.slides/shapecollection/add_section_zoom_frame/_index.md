---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---


## add_section_zoom_frame {#float-float-float-float-isection}
Creates a new Section Zoom frame and adds it to the end of the shape collection.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new Section Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Section Zoom frame, in points. |
| width | **float** | The width of the new Section Zoom frame, in points. |
| height | **float** | The height of the new Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The [`ISection`](/slides/python-net/aspose.slides/isection) referenced by the Section Zoom frame; <br/><br/>            must belong to this presentation and contain at least one slide. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


## add_section_zoom_frame {#float-float-float-float-isection-ippimage}
Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new Section Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Section Zoom frame, in points. |
| width | **float** | The width of the new Section Zoom frame, in points. |
| height | **float** | The height of the new Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The [`ISection`](/slides/python-net/aspose.slides/isection) referenced by the Section Zoom frame; <br/><br/>            must belong to this presentation and contain at least one slide. |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The [`IPPImage`](/slides/python-net/aspose.slides/ippimage) to display within the Section Zoom frame. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced section does not belong to the current presentation or contains no slides. |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

