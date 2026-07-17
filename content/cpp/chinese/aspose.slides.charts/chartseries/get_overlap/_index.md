---
title: get_Overlap()
second_title: Aspose.Slides C++ API 参考
description: 指定二维图表中柱形和条形的重叠程度，以百分比表示（范围为 -100% 到 100%）。此属性不仅属于此系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性为只读。要更改该值，请使用 get_ParentSeriesGroup()->Overlap() 可读写属性。只读 int8_t.
type: docs
weight: 690
url: /zh/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() 方法

指定二维图表中柱形和条形的重叠程度，以百分比表示（范围为 -100% 到 100%）。此属性不仅属于此系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性为只读。要更改该值，请使用 [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 可读写属性。只读 **int8_t**。

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## 备注

Overlap 指定柱形和条形之间的重叠或间距程度，以它们宽度的百分比表示：
* -100%: 最大间距（柱形完全分离）。
* 0%: 柱形并排放置，没有重叠或间距。
* 100%: 最大重叠（柱形完全相互重叠）。 这是属性 [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) 的投影。

## 另请参见

* 类 [ChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)