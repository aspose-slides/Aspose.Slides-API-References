---
title: set_Overlap()
second_title: Aspose.Slides for C++ API Referenciája
description: Megadja, hogy a sávok és oszlopok mennyire fednek át egymást 2-D diagramokon, százalékban (-100% és 100% között).
type: docs
weight: 196
url: /hu/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metódus


Megadja, hogy a sávok és oszlopok mennyire fednek egymást 2-D diagramokon, százalékban (-100% és 100% között).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Megjegyzések


* -100%: Legnagyobb távolság (a sávok teljesen el vannak választva).
* 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100%: Legnagyobb átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság olvasható/írható **int8_t**.



Az alábbi példa bemutatja, hogyan állítható be a átfedés egy diagram sorozatcsoportnál, és hogyan jeleníthető meg a létrehozott diagram egy űrlapon: 
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