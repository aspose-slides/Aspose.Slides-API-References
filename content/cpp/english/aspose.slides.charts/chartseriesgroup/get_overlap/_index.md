---
title: get_Overlap()
second_title: Aspose.Slides for C++ API Reference
description: Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).
type: docs
weight: 157
url: /aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() method


Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Remarks


* -100%: Maximum spacing (bars are completely separated).
* 0%: Bars are placed side by side without overlap or spacing.
* 100%: Maximum overlap (bars completely overlap each other). This property is read/write **int8_t**.



The following example demonstrates how to set the overlap for a chart series group and render the resulting chart on a form: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Set overlap to 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## See Also

* Class [ChartSeriesGroup](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)