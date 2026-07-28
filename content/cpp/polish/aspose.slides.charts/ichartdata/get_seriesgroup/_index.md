---
title: get_SeriesGroup()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: 
type: docs
weight: 222
url: /pl/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metoda




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metoda


Zwraca grupę serii o podanym indeksie.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Uwagi


1) Każda grupa serii zawiera serie o kombinowalnych typach. Grupy kombinowalnych typów serii są zdefiniowane i opisane w wyliczeniu CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są wykreślane na osi podstawowej lub na osi pomocniczej (nie oba przypadki w jednej grupie). Zasada grupowania serii polega więc na grupowaniu według wymienionych wyżej grup typów oraz według typu wykreślania podstawowego/pomocniczego. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie (\"właściwości grupy serii\"). \"Właściwości grupy serii\" w klasie [ChartSeriesGroup](../../chartseriesgroup/) są odczyt/zapis. Każda z \"właściwości grupy serii\" może mieć projekcję tylko do odczytu w klasie [ChartSeries](../../chartseries/). 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartSeriesGroup](../../ichartseriesgroup/)
* Klasa [IChartSeries](../../ichartseries/)
* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)