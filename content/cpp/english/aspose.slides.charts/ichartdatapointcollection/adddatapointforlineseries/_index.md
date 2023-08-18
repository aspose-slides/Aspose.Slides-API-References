---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API Reference
description: Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also ChartTypeCharacterizer.IsChartTypeLine(ChartType) method).
type: docs
weight: 157
url: /aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value. |

### Return Value

New data point.

## IChartDataPointCollection::AddDataPointForLineSeries(double) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) method).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | Data point Value. |

### Return Value

New data point.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)