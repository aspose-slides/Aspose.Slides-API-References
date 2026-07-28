---
title: get_Overlap()
second_title: Aspose.Slides a C++-hoz API referencia
description: Megadja, hogy a 2-D diagramokban a sávok és oszlopok milyen mértékben fednek egymást, százalékban (-100% és 100% között). Ez a tulajdonság nem csak ezen sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik. Ez a szülő sorozatcsoport megfelelő tulajdonságának projekciója, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a get_ParentSeriesGroup()->get(set)_Overlap() olvasás/írás tulajdonságot. Csak olvasható int8_t.
type: docs
weight: 690
url: /hu/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metódus


Megadja, hogy a 2-D diagramokban a sávok és oszlopok milyen mértékben fednek egymást, százalékban (-100% és 100% között). Ez a tulajdonság nem csak ezen sorozatéra vonatkozik, hanem a szülő sorozatcsoport összes sorozatára. Ez a szülő sorozatcsoport megfelelő tulajdonságának projekciója, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() olvasás/írás tulajdonságot. Csak olvasható **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Megjegyzések


Az átfedés meghatározza a sávok és oszlopok közötti átfedés vagy távolság mértékét a szélességük százalékában:* -100%: Maximális távolság (a sávok teljesen szét vannak választva).
* 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
* 100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() tulajdonság projekciója.


## Lásd még

* Osztály [IChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)