---
title: idx_get()
second_title: Aspose.Slides C++ API 参考
description: "获取对应于 Chart::get_ChartData()->get_Series()[0].DataPoints[index] 的图例条目属性，适用于图表类型为以下列表: ChartType::BarOfPie, ChartType::ExplodedPie, ChartType::ExplodedPie3D, ChartType::Pie, ChartType::Pie3D, ChartType::PieOfPie; 或对应于 Chart::get_ChartData()->get_Series()[index] 的其他图表类型。"
type: docs
weight: 14
url: /zh/aspose.slides.charts/legendentrycollection/idx_get/
---
## LegendEntryCollection::idx_get(int32_t) 方法

获取与 [Chart::get_ChartData()](../../chart/get_chartdata/)->get_Series()[0].DataPoints[index] 对应的图例项的属性（当图表类型属于以下列表时：[ChartType::BarOfPie](../../charttype/)、[ChartType::ExplodedPie](../../charttype/)、[ChartType::ExplodedPie3D](../../charttype/)、[ChartType::Pie](../../charttype/)、[ChartType::Pie3D](../../charttype/)、[ChartType::PieOfPie](../../charttype/)）；或在其他图表类型时对应于 [Chart::get_ChartData()](../../chart/get_chartdata/)->get_Series()[index]。

```cpp
System::SharedPtr<ILegendEntryProperties> Aspose::Slides::Charts::LegendEntryCollection::idx_get(int32_t index) override
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ILegendEntryProperties](../../ilegendentryproperties/)
* 类 [LegendEntryCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)