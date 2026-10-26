---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Pobiera grupy serii. Tylko do odczytu IChartSeriesGroupCollection.
type: docs
weight: 27
url: /pl/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metoda

Pobiera grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Uwagi

1) Każda grupa serii zawiera serie o łącznych typach. Grupy łącznych typów serii są definiowane i opisywane przy użyciu wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są wykreślone albo na głównych osiach, albo na osiach pomocniczych (nie oba przypadki w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według wymienionych powyżej grup typów oraz według typu wykreślania główny/pomocniczy.

2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie ("properties grupy serii"). "Properties grupy serii" w klasie [ChartSeriesGroup](../../chartseriesgroup/) jest odczyt/zapis. Każda z "properties grupy serii" może mieć projekcję tylko do odczytu w klasie [ChartSeries](../../chartseries/).

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)