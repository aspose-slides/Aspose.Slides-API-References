---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/hyperlink/__init__/
weight: 10
---


## __init__ {#string}
Creates an instance of a hyperlink.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | string | Hyperlink URL. |



## __init__ {#islide}
Creates an instance of a hyperlink which points to specific slide.
            Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.


```python
def __init__(self, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slide | ISlide | Target slide. |



## __init__ {#hyperlink-string-string-bool-bool-bool}
Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source | Hyperlink | Source hyperlink |
| target_frame | string | Target frame |
| tooltip | string | Tooltip text |
| history | bool |  |
| stop_sounds_on_click | bool |  |
| highlight_click | bool |  |



### See Also
* class [`Hyperlink`](/slides/python-net/aspose.slides/hyperlink)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
