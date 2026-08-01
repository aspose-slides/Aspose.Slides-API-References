---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het leader lines-formaat van gegevenslabels voor. Alleen-lezen IChartLinesFormat.
type: docs
weight: 14
url: /nl/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() methode


Vertegenwoordigt het gegevenslabels leader lines-formaat. Alleen-lezen [IChartLinesFormat](../../ichartlinesformat/).

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartLinesFormat](../../ichartlinesformat/)
* Klasse [IDataLabelCollection](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)