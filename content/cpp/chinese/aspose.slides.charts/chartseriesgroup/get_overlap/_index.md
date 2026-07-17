---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 参考
description: 指定在二维图表中柱形和条形的重叠程度，以百分比表示（范围从 -100% 到 100%）。
type: docs
weight: 157
url: /zh/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() 方法

指定在二维图表中，柱形和条形的重叠程度，以百分比表示（范围从 -100% 到 100%）。

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## 备注

* -100%: 最大间距（栏完全分离）。
* 0%: 栏并排放置，既不重叠也不留间距。
* 100%: 最大重叠（栏完全相互重叠）。此属性是读/写 **int8_t**。

以下示例演示如何为图表系列组设置重叠并在表单上渲染生成的图表：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // 将重叠设置为55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## 另请参见

* 类 [ChartSeriesGroup](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)