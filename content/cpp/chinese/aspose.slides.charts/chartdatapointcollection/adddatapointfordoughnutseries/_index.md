---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参见 ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType) 方法）。"
type: docs
weight: 300
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries/
---
## ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参见 [ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新数据点。

## ChartDataPointCollection::AddDataPointForDoughnutSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参见 [ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(double value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值 |

### 返回值

新数据点。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)