---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidesize/set_size/
weight: 10
---


## set_size {#slidesizetype-slidesizescaletype}
Sets the slide size by type and scales existing content.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Remarks

Assigning any value other than [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) adjusts the [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize/size)
            based on the selected type, while preserving [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation).


## set_size {#float-float-slidesizescaletype}
Sets the slide dimensions explicitly and scales existing content.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Remarks

This resets the [`SlideSize.type`](/slides/python-net/aspose.slides/slidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM)
            and sets the [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation).



### See Also
* class [`SlideSize`](/slides/python-net/aspose.slides/slidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

