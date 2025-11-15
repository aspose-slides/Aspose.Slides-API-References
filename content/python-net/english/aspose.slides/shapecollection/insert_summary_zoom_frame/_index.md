---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---


## insert_summary_zoom_frame {#int-float-float-float-float}
Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

### Returns

The newly created [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Summary Zoom frame. |
| x | **float** | The x-coordinate of the new Summary Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Summary Zoom frame, in points. |
| width | **float** | The width of the new Summary Zoom frame, in points. |
| height | **float** | The height of the new Summary Zoom frame, in points. |

### Remarks

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if the presentation contains no sections, or if the target slide does not belong to any section. |



### See Also
* class [`ISummaryZoomFrame`](/slides/python-net/aspose.slides/isummaryzoomframe)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

