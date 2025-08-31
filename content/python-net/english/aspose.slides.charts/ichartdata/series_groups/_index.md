---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdata/series_groups/
weight: 130
---


## series_groups property
Gets the groups of series.
            Read-only [`IChartSeriesGroupCollection`](/slides/python-net/aspose.slides.charts/ichartseriesgroupcollection).


### Remarks

1) Each group of series contains series with combinable types. Groups of 
            combinable series types defined and described with CombinableSeriesTypesGroup 
            enum.
            Also each group of series contains series witch is plotted whether 
            on primary axes or on secondary axes (not both cases in one group).
            So, principle of series grouping is a grouping by type groups mentioned 
            above and by primary/secondary plotting type.
            
            2) Group of series contains some series properies whitch is common for 
            each series in group ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.

### Definition:
```python
@property
def series_groups(self):
    ...
```


### See Also
* class [`IChartData`](/slides/python-net/aspose.slides.charts/ichartdata)
* class [`IChartSeriesGroupCollection`](/slides/python-net/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

