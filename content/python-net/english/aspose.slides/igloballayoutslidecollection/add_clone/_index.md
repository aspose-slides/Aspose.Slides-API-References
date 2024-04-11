---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---


## add_clone {#ilayoutslide}
Adds a copy of a specified layout slide to the presentation.

### Returns

Added slide.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | ILayoutSlide | Slide to clone. |

### Remarks

When cloning a layout between different presentations layout's master can be cloned too
            to keep source formatting.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.



## add_clone {#ilayoutslide-imasterslide}
Adds a copy of a specified layout slide to the presentation.

### Returns

Added slide.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | ILayoutSlide | Slide to clone. |
| dest_master | IMasterSlide |  |

### Remarks

When cloning a layout between different presentations layout's master can be cloned too
            to keep source formatting.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.



