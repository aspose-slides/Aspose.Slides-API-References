---
title: series_groups property
second_title: Aspose.Slides dla Pythona przy użyciu .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups właściwość
Pobiera grupy serii.
Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection).

### Uwagi

1) Każda grupa serii zawiera serie z łączącymi się typami. Grupy 
            łączących się typów serii są zdefiniowane i opisane w wyliczeniu CombinableSeriesTypesGroup. 
            Ponadto każda grupa serii zawiera serie, które są wykreślane na osi podstawowej 
            lub na osi pomocniczej (nie jednocześnie w jednej grupie). 
            Zatem zasada grupowania serii polega na grupowaniu według wymienionych wyżej grup typów 
            oraz według typu wykreślania podstawowego/pomocniczego.

2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla 
            każdej serii w grupie ("series group properties").
            "Series group properties" w klasie ChartSeriesGroup są odczyt/zapis.
            Każda z "series group properties" może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Definicja:
```python
@property
def series_groups(self):
    ...
```

### Zobacz także
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* klasa [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)