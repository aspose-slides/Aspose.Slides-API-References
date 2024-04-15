---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---


## pie_split_by property
Specifies how to determine which data points are in the second pie or bar 
            on a pie-of-pie or bar-of-pie chart.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.PieSplitBy read/write property for change value.
            Read-only [`PieSplitType`](/slides/python-net/aspose.slides.charts/piesplittype).


### Remarks

1) This is the projection of the property ParentSeriesGroup.PieSplitBy.
            2) If property value is PieSplitType.Custom then you can define custom split 
            information with ParentSeriesGroup.PieSplitCustomPoints property.

### Definition:
```python
@property
def pie_split_by(self):
    ...
```

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
