---
title: get_Overlap()
second_title: Aspose.Slides for C++ API-referencia
description: Meghatározza, hogy a sávok és oszlopok milyen mértékben fednek át egymásra 2-D diagramokon, százalékban (-100%-tól 100%-ig). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra vonatkozik. Ez a megfelelő tulajdonság projekciója a szülő sorozatcsoportban, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a get_ParentSeriesGroup()->Overlap() olvasás/írás tulajdonságot. Csak olvasható int8_t.
type: docs
weight: 690
url: /hu/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metódus


Meghatározza, hogy a sávok és oszlopok milyen mértékben fednek át egymásra 2-D diagramokon, százalékban (-100%-tól 100%-ig). Ez a tulajdonság nem csak erre a sorozatra, hanem az összes szülő sorozatcsoport sorozatra vonatkozik. Ez a megfelelő tulajdonság projekciója a szülő sorozatcsoportban, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) írás/olvasás tulajdonságot. Csak olvasható **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Megjegyzések


Az átfedés megadja a sávok és oszlopok átfedésének vagy távolságának fokát a szélességük százalékában:
* -100%: Maximális távolság (a sávok teljesen el vannak választva).
* 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) tulajdonság projekciója.


## Lásd még

* Osztály [ChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)