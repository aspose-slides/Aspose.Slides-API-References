---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Reprezentuje format linii prowadzących etykiet danych. Tylko do odczytu IChartLinesFormat.
type: docs
weight: 66
url: /pl/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() metoda

Reprezentuje format linii prowadzących etykiet danych. Tylko do odczytu [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## Uwagi

Przykład:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartLinesFormat](../../ichartlinesformat/)
* Klasa [DataLabelCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)