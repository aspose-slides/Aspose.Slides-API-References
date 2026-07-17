---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 参考
description: 指定 2-D 图表中条形和柱形的重叠程度，以百分比表示（从 -100% 到 100%）。该属性不仅属于此系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此该属性为只读。要更改该值，请使用 get_ParentSeriesGroup()->get(set)_Overlap() 读/写属性。只读 int8_t.
type: docs
weight: 690
url: /zh/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() 方法


指定 2-D 图表中条形和柱形的重叠程度，以百分比表示（范围从 -100% 到 100%）。该属性不仅属于此系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此该属性为只读。要更改该值，请使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 读/写属性。只读 **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## 备注


Overlap 指定条形和柱形之间的重叠或间距程度，单位为其宽度的百分比:* -100%: 最大间距（柱完全分离）。
* 0%: 柱并排放置，没有重叠或间距。
* 100%: 最大重叠（柱相互完全重叠）。这是属性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() 的投影。


## 另请参见

* 类 [IChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)