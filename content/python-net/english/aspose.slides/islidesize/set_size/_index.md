---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidesize/set_size/
weight: 10
---


## set_size {#asposeslidesslidesizetype-asposeslidesslidesizescaletype}
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

Assigning any value other than [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) adjusts the [`ISlideSize.size`](/slides/python-net/aspose.slides/islidesize/size)
            based on the selected type, while preserving [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize/orientation).


## set_size {#float-float-asposeslidesslidesizescaletype}
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

This resets the [`ISlideSize.type`](/slides/python-net/aspose.slides/islidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM)
            and sets the [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize/orientation).



### See Also
* class [`ISlideSize`](/slides/python-net/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

