---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---


## add_summary_zoom_frame {#float-float-float-float}
Creates a new Summary Zoom frame and adds it to the end of the shape collection.

### Returns

The newly created [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new Summary Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Summary Zoom frame, in points. |
| width | **float** | The width of the new Summary Zoom frame, in points. |
| height | **float** | The height of the new Summary Zoom frame, in points. |

### Remarks

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if there are no sections in the presentation, or if the target slide does not belong to any section. |



### See Also
* class [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

