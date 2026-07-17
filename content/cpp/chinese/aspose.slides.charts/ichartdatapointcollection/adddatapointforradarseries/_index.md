---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides for C++ API 参考
description: 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。
type: docs
weight: 183
url: /zh/aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries/
---
## IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新数据点。

## IChartDataPointCollection::AddDataPointForRadarSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 [ChartTypeCharacterizer.IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForRadarSeries(double value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值 |

### 返回值

新数据点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [IChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)