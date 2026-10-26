---
title: get_PieSplitBy()
second_title: Aspose.Slides C++ API referencia
description: Azt határozza meg, hogyan kell meghatározni, hogy mely adatpontok vannak a második körön vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a ParentSeriesGroup összes sorozatánál is érvényes – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. Használja a get_ParentSeriesGroup()->get(set)_PieSplitBy() olvasási/írási tulajdonságot az érték módosításához. Csak olvasható PieSplitType.
type: docs
weight: 755
url: /hu/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metódus

Megadja, hogyan kell meghatározni, hogy mely adatpontok vannak a második kör vagy sáv egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoport tulajdonságának leképezése. Ezért ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. Használja a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() olvasható/írható tulajdonságot az érték módosításához. Csak olvasható [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Megjegyzések

1) Ez a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() tulajdonság leképezése. 2) Ha a tulajdonság értéke [PieSplitType::Custom](../../piesplittype/), akkor egyedi felosztási információt definiálhat a [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) tulajdonsággal.

## Lásd még

* Enum [PieSplitType](../../piesplittype/)
* Osztály [ChartSeries](../)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)