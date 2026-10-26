---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ API 參考
description: "建立新的資料點，並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypePie(ChartType) 方法）。"
type: docs
weight: 287
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點，並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 回傳值

新的資料點。

## ChartDataPointCollection::AddDataPointForPieSeries(double) 方法

建立新的資料點，並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 回傳值

新的資料點。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)