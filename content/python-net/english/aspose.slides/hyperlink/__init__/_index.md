---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/hyperlink/__init__/
weight: 10
---


## __init__ {#str}
Creates an instance of a hyperlink.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | Hyperlink URL. |


## __init__ {#asposeslidesislide}
Creates an instance of a hyperlink which points to specific slide.
            Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.


```python
def __init__(self, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Target slide. |


## __init__ {#asposeslideshyperlink-str-str-bool-bool-bool}
Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/aspose.slides/hyperlink) | Source hyperlink |
| target_frame | **str** | Target frame |
| tooltip | **str** | Tooltip text |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### See Also
* class [`Hyperlink`](/slides/python-net/aspose.slides/hyperlink)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

