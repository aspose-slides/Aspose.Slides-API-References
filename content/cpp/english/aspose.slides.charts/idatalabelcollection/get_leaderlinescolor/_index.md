---
title: get_LeaderLinesColor()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the color of all leader lines in the collection. Read System::Drawing::Color."
type: docs
weight: 27
url: /aspose.slides.charts/idatalabelcollection/get_leaderlinescolor/
---
## IDataLabelCollection::get_LeaderLinesColor() method


Gets the color of all leader lines in the collection. Read [System::Drawing::Color](../../../system.drawing/color/).

```cpp
virtual System::Drawing::Color Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesColor()=0
```

## Remarks


Deprecated
:   Use [Aspose.Slides.Charts.IDataLabelCollection](../) instead. The method will be removed after release of version 23.8.


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