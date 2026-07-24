---
title: get_SeriesGroup()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 222
url: /de/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) Methode




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) Methode


Gibt die Gruppe von Reihen am angegebenen Index zurück.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Hinweise


1) Jede Gruppe von Reihen enthält Reihen mit kombinierbaren Typen. Gruppen von kombinierbaren Reihentypen sind im Enumerationstyp CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Reihen Reihen, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Gruppierung von Reihen ist also eine Gruppierung nach den oben genannten Typ-Gruppen und nach dem Primär-/Sekundär-Plott-Typ. 2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in [ChartSeriesGroup](../../chartseriesgroup/) Klasse ist lesbar/schreibbar. Jede der „series group properties“ kann eine schreibgeschützte Projektion in [ChartSeries](../../chartseries/) Klasse haben. 
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)