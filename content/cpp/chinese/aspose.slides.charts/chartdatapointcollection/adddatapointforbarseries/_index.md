---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Column 或 Bar 子类型的系列（另请参见 ChartTypeCharacterizer::IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer::IsChartTypeBar(ChartType) 方法）。"
type: docs
weight: 261
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 [Column](../../../aspose.slides/column/) 或 Bar 子类型的系列（另请参见 [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 和 [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新数据点。

## ChartDataPointCollection::AddDataPointForBarSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 [Column](../../../aspose.slides/column/) 或 Bar 子类型的系列（另请参见 [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 和 [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值 |

### 返回值

新数据点。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)