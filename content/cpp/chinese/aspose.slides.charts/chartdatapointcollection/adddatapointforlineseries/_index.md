---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides C++ API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 ChartTypeCharacterizer::IsChartTypeLine(ChartType) 方法）。"
type: docs
weight: 222
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值。 |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForLineSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值。 |

### 返回值

新的数据点。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)