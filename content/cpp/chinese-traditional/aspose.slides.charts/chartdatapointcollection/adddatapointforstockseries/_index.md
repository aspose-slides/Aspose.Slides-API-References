---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API 參考
description: "建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 ChartTypeCharacterizer::IsChartTypeStock(ChartType) 方法）。"
type: docs
weight: 209
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值。 |

### 傳回值

新資料點。

## ChartDataPointCollection::AddDataPointForStockSeries(double) 方法

建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | **double** | 資料點值。 |

### 傳回值

新資料點。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)