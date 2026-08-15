---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新資料點並將其加入集合的末端。適用於 chartType 為 Doughnut 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method）。
type: docs
weight: 235
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries/
---
## IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) method

建立新資料點並將其加入集合的末端。適用於 chartType 為 Doughnut 子類型之一的序列（另請參閱 [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) method）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 傳回值

新的資料點。

## IChartDataPointCollection::AddDataPointForDoughnutSeries(double) method

建立新資料點並將其加入集合的末端。適用於 chartType 為 Doughnut 子類型之一的序列（另請參閱 [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) method）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(double value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 傳回值

新的資料點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)