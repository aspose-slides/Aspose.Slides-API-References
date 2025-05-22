---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidesize/set_size/
weight: 10
---


## set_size {#slidesizetype-slidesizescaletype}
Sets the type of slide size and scales content using scale type.
Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) will change [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize/size) accordingly, but will keep [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation) intact.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype) | Slide size type. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype) | Scale type of slide content. |


## set_size {#float-float-slidesizescaletype}
Sets the size in points and scales content using scale type.
Assigning any value will reset [`SlideSize.type`](/slides/python-net/aspose.slides/slidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) and set [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation).


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | Width. |
| height | **float** | Height. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype) | Scale type of slide content. |



### See Also
* class [`SlideSize`](/slides/python-net/aspose.slides/slidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

