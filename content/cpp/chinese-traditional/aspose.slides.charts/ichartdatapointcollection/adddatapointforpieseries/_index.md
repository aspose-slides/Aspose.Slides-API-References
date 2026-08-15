---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的資料點並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。
type: docs
weight: 222
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries/
---
## IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 返回值

新的資料點。

## IChartDataPointCollection::AddDataPointForPieSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(double value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 返回值

新的資料點。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)