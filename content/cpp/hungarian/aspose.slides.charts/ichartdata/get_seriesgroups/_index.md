---
title: get_SeriesGroups()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a sorozatok csoportjait. Csak olvasható IChartSeriesGroupCollection.
type: docs
weight: 27
url: /hu/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metódus

Lekéri a sorozatok csoportjait. Csak olvasható [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Megjegyzések

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum határozza meg és írja le. Emellett minden sorozatcsoport olyan sorozatot tartalmaz, amely vagy az elsődleges tengelyeken, vagy a másodlagos tengelyeken kerül ábrázolásra (nem mindkét eset egyszerre egy csoportban). Így a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.

2) A sorozatcsoport olyan sorozattulajdonságokat tartalmaz, amelyek közösek a csoport minden sorozata számára ("series group properties"). "Series group properties" a [ChartSeriesGroup](../../chartseriesgroup/) osztályban olvasható/írható. Minden "series group properties" csak olvasható változatban is létezhet a [ChartSeries](../../chartseries/) osztályban.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Osztály [IChartData](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)