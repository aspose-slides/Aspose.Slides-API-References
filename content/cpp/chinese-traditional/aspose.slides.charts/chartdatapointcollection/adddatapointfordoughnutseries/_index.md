---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 參考文件
description: "建立新的資料點並將其加入集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType) 方法）。"
type: docs
weight: 300
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries/
---
## ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其加入集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值 |

### 返回值

新資料點。

## ChartDataPointCollection::AddDataPointForDoughnutSeries(double) 方法

建立新的資料點並將其加入集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(double value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **double** | 資料點值 |

### 返回值

新資料點。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)