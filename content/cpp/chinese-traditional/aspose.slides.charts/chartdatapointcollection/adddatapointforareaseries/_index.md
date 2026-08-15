---
title: AddDataPointForAreaSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立新的資料點並將其加入集合的末端。適用於 chartType 為 Area 子類型之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeArea(ChartType) 方法）。"
type: docs
weight: 274
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries/
---
## ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Area 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 傳回值

新的資料點。

## ChartDataPointCollection::AddDataPointForAreaSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Area 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(double value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 傳回值

新的資料點。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)