---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 ChartTypeCharacterizer::IsChartTypeStock(ChartType) 方法）。"
type: docs
weight: 209
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值。 |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForStockSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值。 |

### 返回值

新的数据点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)