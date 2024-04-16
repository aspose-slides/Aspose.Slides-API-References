---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---


## add_section_zoom_frame {#float-float-float-float-isection}
Adds a new Section Zoom object to the end of a collection.

### Returns

Created Section Zoom object [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of a new Section Zoom frame **float**. |
| y | **float** | Y coordinate of a new Section Zoom frame **float**. |
| width | **float** | Width of a new Section Zoom frame **float**. |
| height | **float** | Height of a new Section Zoom frame **float**. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The section object referenced by the Section Zoom frame [`ISection`](/slides/python-net/aspose.slides/isection). |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referenced section does not belong to the current presentation or does not contains any slides. |


## add_section_zoom_frame {#float-float-float-float-isection-ippimage}
Adds a new Section Zoom object to the end of a collection with a predefined image.

### Returns

Created Section Zoom object [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of a new Section Zoom frame **float**. |
| y | **float** | Y coordinate of a new Section Zoom frame **float**. |
| width | **float** | Width of a new Section Zoom frame **float**. |
| height | **float** | Height of a new Section Zoom frame **float**. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | The section object referenced by the Section Zoom frame [`ISection`](/slides/python-net/aspose.slides/isection). |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The image for the referenced slide [`IPPImage`](/slides/python-net/aspose.slides/ippimage) |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Referenced section does not belong to the current presentation or does not contains any slides. |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

