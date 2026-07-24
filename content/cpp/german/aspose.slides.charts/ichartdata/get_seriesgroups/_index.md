---
title: get_SeriesGroups()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die Gruppen von Serien. Nur lesbar IChartSeriesGroupCollection.
type: docs
weight: 27
url: /de/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() Methode


Liefert die Gruppen von Serien. Nur lesbar [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Anmerkungen


1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Seriengruppierung ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plot-Typ.

2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind (\"Series group properties\"). \"Series group properties\" in der Klasse [ChartSeriesGroup](../../chartseriesgroup/) ist read/write. Jede der \"Series group properties\" kann eine read-only Projektion in der Klasse [ChartSeries](../../chartseries/) haben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)