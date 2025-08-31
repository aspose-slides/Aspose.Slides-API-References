﻿---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---


## insert_section_zoom_frame {#int-float-float-float-float-asposeslidesisection}
Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Section Zoom frame. |
| x | **float** | The x-coordinate of the new Section Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Section Zoom frame, in points. |
| width | **float** | The width of the new Section Zoom frame, in points. |
| height | **float** | The height of the new Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The [`ISection`](/slides/python-net/aspose.slides/isection) referenced by the Section Zoom frame;<br/><br/>            must belong to this presentation and contain at least one slide. |

### Examples

This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
            (assume that there are at least two sections in the "Presentation.pptx" presentation):

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced section does not belong to the current presentation or contains no slides. |


## insert_section_zoom_frame {#int-float-float-float-float-asposeslidesisection-asposeslidesippimage}
Creates a new Section Zoom frame with a predefined image and inserts it into to the shape
            collection at the specified index.

### Returns

The newly created [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Section Zoom frame. |
| x | **float** | The x-coordinate of the new Section Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Section Zoom frame, in points. |
| width | **float** | The width of the new Section Zoom frame, in points. |
| height | **float** | The height of the new Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The [`ISection`](/slides/python-net/aspose.slides/isection) referenced by the Section Zoom frame;<br/><br/>            must belong to this presentation and contain at least one slide. |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image to display within the Section Zoom frame. |

### Examples

This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
            (assume that there are at least two sections in the "Presentation.pptx" presentation):

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

