---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---


## insert_summary_zoom_frame {#int-float-float-float-float}
Creates a new Summary Zoom object and inserts it to a collection at the specified index.

### Returns

Created Summary Zoom object [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame **float**. |
| y | float | Y coordinate of a new Section Zoom frame **float**. |
| width | float | Width of a new Section Zoom frame **float**. |
| height | float | Height of a new Section Zoom frame **float**. |

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
