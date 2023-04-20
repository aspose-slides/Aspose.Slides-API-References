---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API Reference
description: Gets the groups of series. Read-only IChartSeriesGroupCollection.
type: docs
weight: 27
url: /cpp/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() method


Gets the groups of series. Read-only [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Remarks


1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type.

2) Group of series contains some series properies whitch is common for each series in group (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](../../chartseriesgroup/) class is read/write. Each of \"series group properties\" can have a read-only projection in [ChartSeries](../../chartseries/) class. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)