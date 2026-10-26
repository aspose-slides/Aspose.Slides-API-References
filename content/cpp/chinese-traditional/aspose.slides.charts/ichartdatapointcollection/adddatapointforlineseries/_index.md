---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的資料點並將其加入集合的末端。適用於 chartType 為 Line 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。
type: docs
weight: 157
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Line 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值。 |

### 返回值

新的資料點。

## IChartDataPointCollection::AddDataPointForLineSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Line 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值。 |

### 返回值

新的資料點。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)