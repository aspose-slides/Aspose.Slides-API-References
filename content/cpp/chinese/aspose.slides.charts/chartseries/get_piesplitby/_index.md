---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API 参考
description: 指定如何确定在饼中饼或饼中柱图表上第二个饼或柱中的数据点。该属性不仅属于此系列，还属于父系列组的所有系列——这是相应组属性的投影。因此该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 get_ParentSeriesGroup()->get(set)_PieSplitBy() 读/写属性来更改值。只读 PieSplitType.
type: docs
weight: 755
url: /zh/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() 方法

指定如何确定在饼中饼或饼中柱图表上第二个饼或柱中的数据点。该属性不仅属于此系列，而且属于父系列组的所有系列——这是相应组属性的投影。因此该属性为只读。使用 ParentSeriesGroup 属性来访问父系列组。使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 读/写属性来更改值。只读 [PieSplitType](../../piesplittype/)。

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## 备注

1) 这是属性 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() 的投影。 2) 如果属性值为 [PieSplitType::Custom](../../piesplittype/)，则可以使用 [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) 属性定义自定义拆分信息。

## 另请参见

* 枚举 [PieSplitType](../../piesplittype/)
* 类 [ChartSeries](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)