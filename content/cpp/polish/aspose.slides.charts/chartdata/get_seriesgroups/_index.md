---
title: get_SeriesGroups()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera grupy serii. Tylko do odczytu IChartSeriesGroupCollection.
type: docs
weight: 27
url: /pl/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() metoda


Pobiera grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Uwagi


1) Każda grupa serii zawiera serie o typach możliwych do połączenia. Grupy typów serii, które można łączyć, są definiowane i opisane przy użyciu wyliczenia CombinableSeriesTypesGroup enum. Ponadto każda grupa serii zawiera serie, które są rysowane albo na głównych osiach, albo na drugich osiach (nie oba przypadki w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według wspomnianych wyżej grup typów oraz według typu rysowania głównego/drugiego.

2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie (\"właściwości grupy serii\"). \"Właściwości grupy serii\" w klasie [ChartSeriesGroup](../../chartseriesgroup/) są odczyt/zapis. Każda z \"właściwości grupy serii\" może mieć projekcję tylko do odczytu w klasie [ChartSeries](../../chartseries/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)