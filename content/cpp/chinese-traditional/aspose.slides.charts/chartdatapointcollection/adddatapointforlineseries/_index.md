---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立新的資料點並將其新增至集合的末端。適用於 chartType 為 Line 子類別之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeLine(ChartType) 方法）。"
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其新增至集合的末端。適用於 chartType 為 Line 子類別之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點 Value. |

### Return Value

傳回值

新的資料點。

## ChartDataPointCollection::AddDataPointForLineSeries(double) 方法

建立新的資料點並將其新增至集合的末端。適用於 chartType 為 Line 子類別之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 資料點 Value. |

### Return Value

傳回值

新的資料點。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)