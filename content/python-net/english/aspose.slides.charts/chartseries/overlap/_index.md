---
title: overlap property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartseries/overlap/
weight: 310
---


## overlap property
Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100).
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.Overlap read/write property for change value.
            Read-only **int**.


### Remarks

This is the projection of the property ParentSeriesGroup.Overlap.

### Definition:
```python
@property
def overlap(self):
    ...
```

### See Also
* class [`ChartSeries`](/slides/python-net/aspose.slides.charts/chartseries)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
