---
title: set_Overlap()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel staven en kolommen moeten overlappen op 2-D-diagrammen, als een percentage (van -100% tot 100%).
type: docs
weight: 196
url: /nl/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) methode

Specificeert hoeveel staven en kolommen moeten overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Opmerkingen

* -100%: Maximale spreiding (staven zijn volledig gescheiden).
* 0%: Staven worden naast elkaar geplaatst zonder overlapping of spreiding.
* 100%: Maximale overlapping (staven overlappen elkaar volledig). Deze eigenschap is lees/schrijf **int8_t**.

Het volgende voorbeeld toont hoe de overlapping voor een diagramreeks-groep in te stellen en het resulterende diagram op een formulier te renderen:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Stel overlapping in op 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Zie ook

* Klasse [IChartSeriesGroup](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)