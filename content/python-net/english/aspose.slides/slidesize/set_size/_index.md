---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidesize/set_size/
weight: 20
---


## set_size {#SlideSizeType-SlideSizeScaleType}
Sets the type of slide size and scales content using scale type.
             Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) will change [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize#size) accordingly, but will keep [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation) intact.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | SlideSizeType | Slide size type. |
| scale_type | SlideSizeScaleType | Scale type of slide content. |



## set_size {#float-float-SlideSizeScaleType}
Sets the type of slide size and scales content using scale type.
             Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) will change [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize#size) accordingly, but will keep [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation) intact.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| width | float |  |
| height | float |  |
| scale_type | SlideSizeScaleType | Scale type of slide content. |



