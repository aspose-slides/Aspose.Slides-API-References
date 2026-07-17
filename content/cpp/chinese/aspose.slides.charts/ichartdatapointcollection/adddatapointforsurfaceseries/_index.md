---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides C++ API 参考
description: 创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Surface 子类型之一的系列（另请参见 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。
type: docs
weight: 261
url: /zh/aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries/
---
## IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Surface 子类型之一的序列（另请参见 [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 数据点值 |

### 返回值

新数据点。

## IChartDataPointCollection::AddDataPointForSurfaceSeries(double) 方法

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Surface 子类型之一的序列（另请参见 [ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 方法）。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(double value)=0
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
* 类 [IChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)