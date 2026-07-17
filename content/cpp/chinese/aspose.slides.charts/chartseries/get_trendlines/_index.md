---
title: get_TrendLines()
second_title: Aspose.Slides for C++ API 参考
description: 系列趋势线的集合。只读 ITrendlineCollection.
type: docs
weight: 209
url: /zh/aspose.slides.charts/chartseries/get_trendlines/
---
## ChartSeries::get_TrendLines() 方法

系列趋势线的集合。只读 [ITrendlineCollection](../../itrendlinecollection/).

```cpp
System::SharedPtr<ITrendlineCollection> Aspose::Slides::Charts::ChartSeries::get_TrendLines() override
```

## 备注

TrendLines 在未堆叠的 2-D 区域图、条形图、柱形图、折线图、股票图、xy（scatter）图和气泡图中的数据系列是可用的（非空）。trendline 在任何堆叠或 3-D 图表类型中的数据系列不可用。Trendlines 在雷达图、饼图、曲面图或环形图中也不可用。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ITrendlineCollection](../../itrendlinecollection/)
* 类 [ChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)