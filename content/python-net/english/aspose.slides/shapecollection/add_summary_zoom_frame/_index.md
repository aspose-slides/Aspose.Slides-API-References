---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---


## add_summary_zoom_frame {#float-float-float-float}
Adds a new Summary Zoom object to the end of a collection.

### Returns

Created Summary Zoom object [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X coordinate of a new Section Zoom frame **float**. |
| y | **float** | Y coordinate of a new Section Zoom frame **float**. |
| width | **float** | Width of a new Section Zoom frame **float**. |
| height | **float** | Height of a new Section Zoom frame **float**. |

### Remarks

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation.

## Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | There are no sections in the presentation, or the target slide does not belong to any section. |



### See Also
* class [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

