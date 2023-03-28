---
title: set_LeaderLinesColor()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the color of all leader lines in the collection. Write System::Drawing::Color."
type: docs
weight: 79
url: /cpp/aspose.slides.charts/datalabelcollection/set_leaderlinescolor/
---
## DataLabelCollection::set_LeaderLinesColor([System::Drawing::Color](../../../system.drawing/color/)) method


Sets the color of all leader lines in the collection. Write [System::Drawing::Color](../../../system.drawing/color/).

```cpp
void Aspose::Slides::Charts::DataLabelCollection::set_LeaderLinesColor(System::Drawing::Color value) override
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto chart = System::ExplicitCast<IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto series = chart->get_ChartData()->get_Series();
auto labels = series->idx_get(0)->get_Labels();

labels->set_LeaderLinesColor(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```




## See Also

* Class [Color](../../../system.drawing/color/)
* Class [DataLabelCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
