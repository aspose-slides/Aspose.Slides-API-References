---
title: get_SeriesGroup()
second_title: Aspose.Slides a C++ API hivatkozása
description: 
type: docs
weight: 222
url: /hu/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metódus

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metódus

Visszaadja a megadott indexű sorozatcsoportot.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Megjegyzések

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum határozza meg és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy az elsődleges tengelyen, vagy a másodlagos tengelyen ábrázolva vannak (nem mindkét eset egyszerre egy csoportban). Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.
2) A sorozatcsoport néhány olyan sorozattulajdonságot tartalmaz, amely minden sorozatra jellemző a csoportban („sorozatcsoport tulajdonságok”). A „sorozatcsoport tulajdonságok” a [ChartSeriesGroup](../../chartseriesgroup/) osztályban olvasás/írás. Minden egyes „sorozatcsoport tulajdonságnak” lehet csak olvasható leképezése a [ChartSeries](../../chartseries/) osztályban.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartSeriesGroup](../../ichartseriesgroup/)
* Osztály [IChartSeries](../../ichartseries/)
* Osztály [IChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)