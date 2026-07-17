---
title: AddDataPointForScatterSeries()
second_title: Aspose.Slides C++ API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer::IsChartTypeScatter(ChartType) 方法）。"
type: docs
weight: 235
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries/
---
## ChartDataPointCollection::AddDataPointForScatterSeries(System::SharedPtr\<IChartDataCell\>, System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(System::SharedPtr<IChartDataCell> xValue, System::SharedPtr<IChartDataCell> yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点 XValue |
| yValue | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点 YValue |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForScatterSeries(double, System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(double xValue, System::SharedPtr<IChartDataCell> yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | **double** | 数据点 XValue |
| yValue | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点 YValue |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForScatterSeries(System::String, System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(System::String xValue, System::SharedPtr<IChartDataCell> yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [System::String](../../../system/string/) | 数据点 XValue |
| yValue | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点 YValue |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForScatterSeries(System::SharedPtr\<IChartDataCell\>, double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(System::SharedPtr<IChartDataCell> xValue, double yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点 XValue |
| yValue | **double** | 数据点 YValue |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForScatterSeries(double, double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(double xValue, double yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | **double** | 数据点 XValue |
| yValue | **double** | 数据点 YValue |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForScatterSeries(System::String, double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeScatter(ChartType)](../../charttypecharacterizer/ischarttypescatter/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForScatterSeries(System::String xValue, double yValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [System::String](../../../system/string/) | 数据点 XValue |
| yValue | **double** | 数据点 YValue |

### 返回值

新的数据点。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)