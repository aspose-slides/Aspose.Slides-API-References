---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 参考
description: 指定如何确定在 pie-of-pie 或 bar-of-pie 图表上第二个饼或条形中的数据点。此属性不仅属于此系列，还属于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性来访问父系列组。使用 get_ParentSeriesGroup()->get(set)_PieSplitBy() 可读写属性来更改值。只读 PieSplitType.
type: docs
weight: 729
url: /zh/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() 方法

指定如何确定在 pie-of-pie 或 bar-of-pie 图表上第二个饼或条形中的数据点。此属性不仅属于此系列，还属于父系列组的所有系列——这是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性来访问父系列组。使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 可读写属性来更改值。只读 [PieSplitType](../../piesplittype/)。

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## 备注

1) 这是属性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 的投影。 2) 如果属性值为 [PieSplitType::Custom](../../piesplittype/)，则可以使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 属性定义自定义拆分信息。

## 另请参阅

* 枚举 [PieSplitType](../../piesplittype/)
* 类 [IChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)