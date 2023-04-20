---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API Reference
description: Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also ChartTypeCharacterizer.IsChartTypeColumn(ChartType) and ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).
type: docs
weight: 196
url: /cpp/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of [Column](../../../aspose.slides/column/) or Bar subtypes (see also [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) and [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### Return Value

New data point.

## IChartDataPointCollection::AddDataPointForBarSeries(double) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of [Column](../../../aspose.slides/column/) or Bar subtypes (see also [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) and [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | Data point Value |

### Return Value

New data point.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)