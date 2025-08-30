---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---


## add_clone {#asposeslidesilayoutslide}
Adds a copy of a specified layout slide to the presentation.

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

When cloning a layout between different presentations layout's master can be cloned too
            to keep source formatting.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.


## add_clone {#asposeslidesilayoutslide-asposeslidesimasterslide}
Adds a copy of a specified layout slide to the presentation.

### Returns

Added slide.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide) | Master slide for a new layout. |

### Remarks

1) New layout will be linked with defined master in destination presentation.
            So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.
            2) Analogue of this method is method [`IMasterLayoutSlideCollection.add_clone`](/slides/python-net/aspose.slides/imasterlayoutslidecollection/add_clone)
            accessed with [`IMasterSlide.layout_slides`](/slides/python-net/aspose.slides/imasterslide/layout_slides) property.



### See Also
* class [`GlobalLayoutSlideCollection`](/slides/python-net/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

