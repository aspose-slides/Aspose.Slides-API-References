---
title: get_LeaderLinesColor()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the color of all leader lines in the collection. Read System::Drawing::Color."
type: docs
weight: 79
url: /aspose.slides.charts/datalabelcollection/get_leaderlinescolor/
---
## DataLabelCollection::get_LeaderLinesColor() method


Gets the color of all leader lines in the collection. Read [System::Drawing::Color](../../../system.drawing/color/).

```cpp
System::Drawing::Color Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesColor() override
```

## Remarks


Deprecated
:   Use [Aspose.Slides.Charts.IDataLabelCollection](../../idatalabelcollection/) instead. The method will be removed after release of version 23.8.


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