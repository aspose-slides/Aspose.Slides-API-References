---
title: get_Overlap()
second_title: Aspose.Slides C++ API hivatkozás
description: Megadja, hogy a 2-D diagramok oszlopai és sávjai mennyire fedik át egymást, százalékban (-100%-tól 100%-ig).
type: docs
weight: 157
url: /hu/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() metódus

Megadja, hogy a 2-D diagramok oszlopai és sávjai mennyire fedik át egymást, százalékban (-100 % és 100 % között).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Megjegyzések

* -100 %: Maximális távolság (az oszlopok teljesen el vannak választva).
* 0 %: Az oszlopok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100 %: Maximális átfedés (az oszlopok teljesen átfedik egymást). Ez a tulajdonság írható/olvasható **int8_t**.

A következő példa bemutatja, hogyan lehet beállítani az átfedést egy diagram sorozatcsoportnál, és megjeleníteni a kapott diagramot egy űrlapon:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Átfedés beállítása 55%-ra

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Lásd még

* Osztály [ChartSeriesGroup](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)