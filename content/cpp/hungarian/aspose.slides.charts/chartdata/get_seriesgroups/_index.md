---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API referencia
description: A sorozatok csoportjait adja vissza. Csak olvasható IChartSeriesGroupCollection.
type: docs
weight: 27
url: /hu/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() metódus


A sorozatok csoportjait adja vissza. Csak olvasható [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Megjegyzések


1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum határozza meg és írja le. Továbbá minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy elsődleges tengelyen, vagy másodlagos tengelyen vannak ábrázolva (nem mindkét eset egy csoportban). Így a sorozatok csoportosításának elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.

2) A sorozatcsoport néhány sorozati tulajdonságot tartalmaz, amelyek közösek a csoport minden sorozatára (\"Series group properties\"). \"Series group properties\" a [ChartSeriesGroup](../../chartseriesgroup/) osztályban olvasás/írás. Minden \"Series group properties\" rendelkezhet csak olvasható leképezéssel a [ChartSeries](../../chartseries/) osztályban. 

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Osztály [ChartData](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)