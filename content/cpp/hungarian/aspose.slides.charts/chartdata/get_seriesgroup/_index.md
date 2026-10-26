---
title: get_SeriesGroup()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 222
url: /hu/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metódus




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metódus


Visszaadja a sorozatok csoportját a megadott indexnél.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Megjegyzések


1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum definiálja és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy elsődleges tengelyeken vagy másodlagos tengelyeken vannak ábrázolva (nem mindkét eset egyszerre egy csoportban). Így a sorozatok csoportosításának elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás. 2) A sorozatcsoport néhány sorozati tulajdonságot tartalmaz, amely közös minden sorozatra a csoportban ("series group properties"). "Series group properties" a [ChartSeriesGroup](../../chartseriesgroup/) osztályban olvasás/írás. Minden "series group properties" csak-olvasású nézetet kaphat a [ChartSeries](../../chartseries/) osztályban. 
## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartSeriesGroup](../../ichartseriesgroup/)
* Osztály [IChartSeries](../../ichartseries/)
* Osztály [ChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)