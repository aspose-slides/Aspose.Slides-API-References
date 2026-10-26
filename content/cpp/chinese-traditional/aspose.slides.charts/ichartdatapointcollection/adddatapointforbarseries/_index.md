---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的資料點並將其加入集合的末端。適用於 chartType 為 Column 或 Bar 子類型的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。
type: docs
weight: 196
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 [Column](../../../aspose.slides/column/) 或 Bar 子類型的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 和 [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 回傳值

新的資料點。

## IChartDataPointCollection::AddDataPointForBarSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於 chartType 為 [Column](../../../aspose.slides/column/) 或 Bar 子類型的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 和 [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 回傳值

新的資料點。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)