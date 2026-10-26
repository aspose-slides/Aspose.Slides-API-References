---
title: get_PieSplitBy()
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza, hogyan kell eldönteni, mely adatok szerepelnek a második tortán vagy oszlopon egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak az aktuális sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoporttulajdonság projekciója. Ennek következtében ez a tulajdonság csak olvasható. A ParentSeriesGroup tulajdonságot használja a szülő sorozatcsoport eléréséhez. Használja a get_ParentSeriesGroup()->get(set)_PieSplitBy() írás/olvasás tulajdonságot az érték módosításához. PieSplitType csak olvasható.
type: docs
weight: 729
url: /hu/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metódus

Megadja, hogyan kell meghatározni, mely adatpontok szerepelnek a második tortán vagy oszlopon egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak az aktuális sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoporttulajdonság projekciója. Ezért ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. Használja a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() írás/olvasás tulajdonságot az érték módosításához. [PieSplitType](../../piesplittype/) csak olvasható.

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Megjegyzések

1) Ez a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() tulajdonság projekciója. 2) Ha a tulajdonság értéke [PieSplitType::Custom](../../piesplittype/), akkor egyéni felosztási információt definiálhat a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) tulajdonsággal. 

## Lásd még

* Enum [PieSplitType](../../piesplittype/)
* Osztály [IChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)