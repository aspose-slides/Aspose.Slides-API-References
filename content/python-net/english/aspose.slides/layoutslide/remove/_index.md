---
title: remove method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/layoutslide/remove/
weight: 60
---


## remove {#}
Removes layout from presentation.


```python
def remove(self):
    ...
```


### Remarks

To avoid throwing of the PptxEditException check layout's HasDependingSlides property before.

## Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if layout is already removed from presentation or if layout is used in presentation (its <br/>            HasDependingSlides property is true). |



