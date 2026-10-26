---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 参考
description: 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。
type: docs
weight: 235
url: /zh/aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries/
---
## IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新的数据点。

## IChartDataPointCollection::AddDataPointForDoughnutSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 [ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(double value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值 |

### 返回值

新的数据点。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [IChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)