---
title: get_Overlap()
second_title: Aspose.Slides C++ API referencia
description: Megadja, hogy a sávok és oszlopok mekkora mértékben fednek át 2-D diagramokon, százalékban (-100% és 100% között).
type: docs
weight: 183
url: /hu/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() metódus

Megadja, hogy a sávok és oszlopok milyen mértékben fednek át egymást 2-D diagramokon, százalékban (from -100% to 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Megjegyzések

* -100%: Maximális távolság (a sávok teljesen szétváltak).
* 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság olvasás/írás **int8_t**.

A következő példa bemutatja, hogyan állítható be az átfedés egy diagram sorozatcsoportnál, és hogyan jeleníthető meg a kapott diagram egy űrlapon:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Állítsa be az átfedést 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Lásd még

* Osztály [IChartSeriesGroup](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)