---
title: series_groups property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups egenskap
Gets the groups of series.
            Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection).

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

### Se även
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* klass [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)