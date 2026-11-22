---
title: series_groups property
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups właściwość
Pobiera grupy serii.
Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection).

### Uwagi

1) Każda grupa serii zawiera serie o typach łączonych. Grupy typów łączonych serii są zdefiniowane i opisane przy użyciu wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są rysowane albo na osi głównej, albo na osi pomocniczej (nie oba przypadki w jednej grupie). Zasada grupowania serii polega więc na grupowaniu wg wymienionych wyżej grup typów oraz wg typu rysowania na osi głównej/pomocniczej.

2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Definicja:
```python
@property
def series_groups(self):
    ...
```

### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* klasa [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)