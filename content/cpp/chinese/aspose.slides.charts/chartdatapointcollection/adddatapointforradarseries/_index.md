---
title: AddDataPointForRadarSeries()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: "创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 ChartTypeCharacterizer::IsChartTypeRadar(ChartType) 方法）。"
type: docs
weight: 248
url: /zh/aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries/
---
## ChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr\<IChartDataCell\>) 方法


创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForRadarSeries(System::SharedPtr<IChartDataCell> value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新的数据点。

## ChartDataPointCollection::AddDataPointForRadarSeries(double) 方法


创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 [ChartTypeCharacterizer::IsChartTypeRadar(ChartType)](../../charttypecharacterizer/ischarttyperadar/) 方法）。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForRadarSeries(double value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 数据点值 |

### 返回值

新的数据点。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)