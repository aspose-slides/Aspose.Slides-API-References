---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides pro C++ – reference API
description: Zastupuje formát vodicích čar popisků dat. Pouze pro čtení IChartLinesFormat.
type: docs
weight: 66
url: /cs/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() metoda


Zastupuje formát vodicích čar popisků dat. Pouze pro čtení [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## Poznámky


Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartLinesFormat](../../ichartlinesformat/)
* Třída [DataLabelCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)