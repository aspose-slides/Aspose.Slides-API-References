---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides C++-hez API referencia
description: Képviseli az adatcímkék vezetővonalainak formátumát. Csak olvasható IChartLinesFormat.
type: docs
weight: 66
url: /hu/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() metódus

Képviseli az adatcímkék vezetővonalainak formátumát. Csak olvasható [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## Megjegyzések

Példa:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartLinesFormat](../../ichartlinesformat/)
* Osztály [DataLabelCollection](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)