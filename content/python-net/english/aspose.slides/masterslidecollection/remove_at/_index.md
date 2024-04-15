---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/masterslidecollection/remove_at/
weight: 40
---


## remove_at {#int}
Removes the element at the specified index of the collection.


```python
def remove_at(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index of the element to remove. |

### Remarks

To avoid throwing of the PptxEditException check master's HasDependingSlides property before.

## Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if the master to remove is used in presentation (its HasDependingSlides property is true). |



### See Also
* class [`MasterSlideCollection`](/slides/python-net/aspose.slides/masterslidecollection)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
