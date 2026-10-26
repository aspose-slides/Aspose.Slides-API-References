---
title: get_Overlap()
second_title: Aspose.Slides for C++ API-referentie
description: Specifieert hoeveel balken en kolommen moeten overlappen op 2-D grafieken, als een percentage (van -100% tot 100%).
type: docs
weight: 157
url: /nl/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() methode


Specificeert hoeveel balken en kolommen moeten overlappen op 2-D charts, als een percentage (van -100% tot 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Opmerkingen


* -100%: Maximale afstand (balken zijn volledig gescheiden).
* 0%: Balken worden naast elkaar geplaatst zonder overlap of afstand.
* 100%: Maximale overlap (balken overlappen elkaar volledig). Deze eigenschap is lees/schrijf **int8_t**.



Het volgende voorbeeld laat zien hoe u de overlapping voor een ChartSeriesGroup instelt en het resulterende diagram rendert op een formulier: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Stel overlap in op 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Zie ook

* Klasse [ChartSeriesGroup](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)