---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API Reference
description: "Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also ChartTypeCharacterizer::IsChartTypeStock(ChartType) method)."
type: docs
weight: 209
url: /aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) method).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value. |

### Return Value

New data point.

## ChartDataPointCollection::AddDataPointForStockSeries(double) method


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) method).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
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
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)