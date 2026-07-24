---
title: get_SeriesGroup()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 222
url: /de/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) Methode




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) Methode


Gibt die Gruppe von Serien am angegebenen Index zurück.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Anmerkungen


1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden durch das Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen geplottet werden (nicht beides in einer Gruppe). Das Prinzip der Seriendefinition ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp. 2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("Seriengruppen-Eigenschaften"). "Seriengruppen-Eigenschaften" in der [ChartSeriesGroup](../../chartseriesgroup/) Klasse sind les-/schreibbar. Jede "Seriengruppen-Eigenschaften" kann eine Nur-Lese-Projektion in der [ChartSeries](../../chartseries/) Klasse haben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)