---
title: get_Overlap()
second_title: Aspose.Slides for C++ API 参考
description: 指定 2-D 图表中的条形和柱状图的重叠程度，以百分比表示（范围从 -100% 到 100%）。
type: docs
weight: 183
url: /zh/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() 方法


指定 2-D 图表中的条形和柱状图的重叠程度，以百分比表示（范围从 -100% 到 100%）。

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## 备注


* -100%：最大间距（条形完全分离）。
* 0%：条形并排放置，既不重叠也没有间距。
* 100%：最大重叠（条形彼此完全重叠）。此属性为可读写 **int8_t**。



下面的示例演示了如何为图表系列组设置重叠并在表单上呈现生成的图表： 
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

* Class [IChartSeriesGroup](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)