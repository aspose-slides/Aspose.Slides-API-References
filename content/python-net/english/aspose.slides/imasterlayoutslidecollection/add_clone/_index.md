﻿---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---


## add_clone {#ilayoutslide}
Adds a copy of a specified layout slide to the end of the collection.

### Returns

Added slide.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide) | Slide to clone. |

### Remarks

1) New layout will be linked with parent master slide for this layout slides collection.
            So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.
            2) Analogue of this method is method [`IGlobalLayoutSlideCollection.add_clone`](/slides/python-net/aspose.slides/igloballayoutslidecollection/add_clone)
            accessed with [`IPresentation.layout_slides`](/slides/python-net/aspose.slides/ipresentation/layout_slides) property.



### See Also
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`IMasterLayoutSlideCollection`](/slides/python-net/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

