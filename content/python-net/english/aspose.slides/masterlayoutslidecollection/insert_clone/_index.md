---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 60
---


## insert_clone {#int-ILayoutSlide}
Inserts a copy of a specified layout slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new slide. |
| source_layout | ILayoutSlide | Slide to clone. |

### Remarks

New layout will be linked with parent master slide for this layout slides collection.
            So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.



