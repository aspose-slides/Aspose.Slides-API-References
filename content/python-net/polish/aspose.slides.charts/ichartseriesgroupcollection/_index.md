---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides dla Pythona przy użyciu .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection klasa

Reprezentuje kolekcję grup kombinowalnych serii.

Typ IChartSeriesGroupCollection udostępnia następujące elementy:

Pobiera grupę serii według indeksu.

## Indexer

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |

### Uwagi

1) Każda grupa serii zawiera serie z kombinowalnymi typami. Grupy 
            kombinowalnych typów serii zdefiniowane i opisane przy pomocy wyliczenia CombinableSeriesTypesGroup 
            enum.
            Ponadto każda grupa serii zawiera serie, które są rysowane czy to 
            na osi głównej, czy na osi pomocniczej (nie oba przypadki w jednej grupie).
            Zatem zasada grupowania serii to grupowanie według wymienionych 
            wyżej grup typów oraz według typu rysowania na osi głównej/pomocniczej.
            
            2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla 
            każdej serii w grupie („właściwości grupy serii”).
            „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis.
            Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)