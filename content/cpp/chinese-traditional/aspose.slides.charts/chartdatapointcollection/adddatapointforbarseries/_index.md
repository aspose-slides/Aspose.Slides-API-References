---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立新的資料點並將其加入集合的末端。適用於圖表類型為 Column 或 Bar 子類型的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeColumn(ChartType) 與 ChartTypeCharacterizer::IsChartTypeBar(ChartType) 方法）。"
type: docs
weight: 261
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於圖表類型為 [Column](../../../aspose.slides/column/) 或 Bar 子類型的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 與 [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 回傳值

新的資料點。

## ChartDataPointCollection::AddDataPointForBarSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於圖表類型為 [Column](../../../aspose.slides/column/) 或 Bar 子類型的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 與 [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 回傳值

新的資料點。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)