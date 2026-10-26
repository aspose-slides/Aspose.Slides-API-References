---
title: set_Overlap()
second_title: Aspose.Slides for C++ API-referencia
description: Megadja, hogy a sávok és oszlopok milyen mértékben fednek át 2-D diagramokon, százalékban (-100% és 100% között).
type: docs
weight: 170
url: /hu/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) metódus

Megadja, hogy a 2-D diagramokon a sávok és oszlopok milyen mértékben átfednek, százalékban (-100% és 100% között).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Megjegyzések

* -100%: Maximális távolság (az oszlopok teljesen el vannak különítve).
* 0%: Az oszlopok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100%: Maximális átfedés (az oszlopok teljesen átfedik egymást). Ez a tulajdonság olvasható/írható **int8_t**.

Az alábbi példa bemutatja, hogyan állítható be a átfedés egy diagram sorozatcsoportban, és hogyan jeleníthető meg a kapott diagram egy űrlapon:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Állítsa be az átfedést 55%-ra

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Lásd még

* Osztály [ChartSeriesGroup](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)