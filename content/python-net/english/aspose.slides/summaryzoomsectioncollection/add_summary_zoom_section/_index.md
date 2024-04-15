---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---


## add_summary_zoom_section {#isection}
Creates new Summary Zoom Section object and add it to the collection

### Returns

Added [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe) element



```python
def add_summary_zoom_section(self, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| section | ISection | Section for a new Summary Zoom Section element [`ISection`](/slides/python-net/aspose.slides/isection) |

### Remarks

If an element for this section already exists in the collection, the existing element is returned.

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentException** | Referenced section does not belong to the current presentation or does not contains any slides. |



### See Also
* class [`ISection`](/slides/python-net/aspose.slides/isection)
* class [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe)
* class [`SummaryZoomSectionCollection`](/slides/python-net/aspose.slides/summaryzoomsectioncollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
