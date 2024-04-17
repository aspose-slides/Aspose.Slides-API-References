---
title: remove method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/layoutslidecollection/remove/
weight: 20
---


## remove {#ilayoutslide}
Removes a layout from the collection.


```python
def remove(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide) | The layout slide to remove from the collection. |

### Remarks

1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before.
            2) You can use also [`ILayoutSlide.remove`](/slides/python-net/aspose.slides/ilayoutslide/remove) method to simplify code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if layout is used in presentation (its HasDependingSlides property is true). |



### See Also
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`LayoutSlideCollection`](/slides/python-net/aspose.slides/layoutslidecollection)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

