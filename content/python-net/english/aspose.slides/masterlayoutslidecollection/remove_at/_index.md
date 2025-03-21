﻿---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---


## remove_at {#int}
Removes the element at the specified index of the collection.


```python
def remove_at(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index of the element to remove. |

### Remarks

1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before.
            2) You can use also [`ILayoutSlide.remove`](/slides/python-net/aspose.slides/ilayoutslide/remove) method to simplify code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if layout is used in presentation (its HasDependingSlides property is true). |



### See Also
* class [`MasterLayoutSlideCollection`](/slides/python-net/aspose.slides/masterlayoutslidecollection)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

