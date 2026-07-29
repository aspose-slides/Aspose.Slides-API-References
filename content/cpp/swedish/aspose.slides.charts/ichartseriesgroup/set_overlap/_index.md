---
title: set_Overlap()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100% till 100%).
type: docs
weight: 196
url: /sv/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metod

Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100% till 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Anmärkningar

* -100%: Maximalt avstånd (staplar är helt separerade).
* 0%: Staplar placeras sida vid sida utan överlapp eller avstånd.
* 100%: Maximal överlappning (staplar överlappar varandra helt). Denna egenskap är läs/skriv **int8_t**.

Följande exempel visar hur man ställer in överlappning för en diagramseriegrupp och renderar det resulterande diagrammet på ett formulär: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Ställ in överlappning till 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Se även

* Klass [IChartSeriesGroup](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)