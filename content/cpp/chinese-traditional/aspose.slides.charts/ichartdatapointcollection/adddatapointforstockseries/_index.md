---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。
type: docs
weight: 144
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) 方法

建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 資料點值。 |

### 回傳值

新的資料點。

## IChartDataPointCollection::AddDataPointForStockSeries(double) 方法

建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 資料點值。 |

### 回傳值

新的資料點。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)