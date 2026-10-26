---
title: get_SeriesGroups()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Gruppen von Datenreihen. Nur lesbar IChartSeriesGroupCollection.
type: docs
weight: 27
url: /de/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() Methode

Ermittelt die Gruppen von Datenreihen. Nur lesbar [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Hinweise

1) Jede Gruppe von Datenreihen enthält Datenreihen mit kombinierbaren Typen. Gruppen von kombinierbaren Datenreihentypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Datenreihen Datenreihen, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beides in einer Gruppe). Daher basiert das Prinzip der Datenreihengruppierung auf einer Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp.

2) Eine Gruppe von Datenreihen enthält einige Eigenschaften, die für jede Datenreihe in der Gruppe gemeinsam sind (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](../../chartseriesgroup/) Klasse ist Lesen/Schreiben. Jede \"series group properties\" kann eine Nur lesbar Projektion in [ChartSeries](../../chartseries/) Klasse haben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)