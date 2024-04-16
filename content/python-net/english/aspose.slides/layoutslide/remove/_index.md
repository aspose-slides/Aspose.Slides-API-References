---
title: remove method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
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



### See Also
* class [`LayoutSlide`](/slides/python-net/aspose.slides/layoutslide)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

