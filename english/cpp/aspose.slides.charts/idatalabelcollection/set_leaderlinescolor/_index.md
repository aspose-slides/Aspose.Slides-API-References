---
title: set_LeaderLinesColor()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the color of all leader lines in the collection. Write System::Drawing::Color."
type: docs
weight: 27
url: /cpp/aspose.slides.charts/idatalabelcollection/set_leaderlinescolor/
---
## IDataLabelCollection::set_LeaderLinesColor([System::Drawing::Color](../../../system.drawing/color/)) method


Sets the color of all leader lines in the collection. Write [System::Drawing::Color](../../../system.drawing/color/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelCollection::set_LeaderLinesColor(System::Drawing::Color value)=0
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
* Class [IDataLabelCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
