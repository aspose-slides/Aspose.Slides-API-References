---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_zoom_frame/
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

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentException** | Referenced slide does not belong to the current presentation. |



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

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentException** | Referenced slide does not belong to the current presentation. |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/aspose.slides/izoomframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
