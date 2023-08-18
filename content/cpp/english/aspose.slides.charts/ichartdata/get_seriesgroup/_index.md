---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 209
url: /aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) method




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) method


Returns the group of series at the specified index.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Remarks


1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](../../chartseriesgroup/) class is read/write. Each of \"series group properties\" can have a read-only projection in [ChartSeries](../../chartseries/) class. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)