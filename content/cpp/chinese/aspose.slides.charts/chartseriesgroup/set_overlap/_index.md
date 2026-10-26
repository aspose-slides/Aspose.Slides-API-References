---
title: set_Overlap()
second_title: Aspose.Slides for C++ API 参考
description: 指定在二维图表中条形和柱形的重叠程度，以百分比表示（从 -100% 到 100%）。
type: docs
weight: 170
url: /zh/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) 方法

指定在 2-D 图表中条形和柱形的重叠程度，作为百分比（-100% 到 100%）。

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## 备注

* -100%：最大间距（条形完全分离）。
* 0%：条形并排放置，无重叠或间距。
* 100%：最大重叠（条形完全相互覆盖）。此属性为可读/可写 **int8_t**。

以下示例演示如何为图表系列组设置重叠并在表单上渲染生成的图表：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 将重叠设置为 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## 参见

* 类 [ChartSeriesGroup](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)