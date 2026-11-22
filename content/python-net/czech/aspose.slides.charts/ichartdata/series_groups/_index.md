---
title: series_groups property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups vlastnost
Gets the groups of series.
            Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection).

### Poznámky

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

### Definice:
```python
@property
def series_groups(self):
    ...
```

### Viz také
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* třída [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)