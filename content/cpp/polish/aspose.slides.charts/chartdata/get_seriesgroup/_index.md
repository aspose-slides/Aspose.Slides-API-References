---
title: get_SeriesGroup()
second_title: Aspose.Slides dla C++ – odniesienie API
description: 
type: docs
weight: 222
url: /pl/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metoda




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metoda


Zwraca grupę serii o podanym indeksie.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Uwagi


1) Każda grupa serii zawiera serie z łącznymi typami. Grupy łącznych typów serii są zdefiniowane i opisane przy pomocy wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są wykreślane albo na głównych osiach, albo na dodatkowych osiach (nie oba przypadki w jednej grupie). Zasada grupowania serii polega więc na grupowaniu według wymienionych wyżej grup typów oraz według typu wykreślania główne/dodatkowe. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie (\"właściwości grupy serii\"). \"Właściwości grupy serii\" w klasie [ChartSeriesGroup](../../chartseriesgroup/) są odczyt-zapis. Każde z \"właściwości grupy serii\" może mieć wersję tylko do odczytu w klasie [ChartSeries](../../chartseries/). 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasa [IChartSeries](../../ichartseries/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)