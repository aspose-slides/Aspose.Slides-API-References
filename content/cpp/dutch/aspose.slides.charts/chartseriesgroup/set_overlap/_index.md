---
title: set_Overlap()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel balken en kolommen moeten overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%).
type: docs
weight: 170
url: /nl/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) methode


Specificeert hoeveel balken en kolommen op 2-D charts overlappen, als een percentage (van -100% tot 100%).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Opmerkingen


* -100%: Maximale afstand (balken zijn volledig gescheiden).
* 0%: Balken worden naast elkaar geplaatst zonder overlap of afstand.
* 100%: Maximale overlap (balken overlappen elkaar volledig). Deze eigenschap is lees/schrijf **int8_t**.



Het volgende voorbeeld laat zien hoe de overlap voor een ChartSeriesGroup wordt ingesteld en hoe het resulterende chart op een formulier wordt gerenderd: 
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