---
title: get_Overlap()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel balken en kolommen moeten overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%).
type: docs
weight: 183
url: /nl/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() methode


Specificeert hoeveel balken en kolommen moeten overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Opmerkingen


* -100%: Maximale spatiëring (balken zijn volledig gescheiden).
* 0%: Balken worden naast elkaar geplaatst zonder overlapping of spatiëring.
* 100%: Maximale overlapping (balken overlappen volledig elkaar). Deze eigenschap is lezen/schrijven **int8_t**.



Het volgende voorbeeld toont hoe u de overlap voor een chart series group instelt en de resulterende diagram rendert op een formulier: 
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

* Klasse [IChartSeriesGroup](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)