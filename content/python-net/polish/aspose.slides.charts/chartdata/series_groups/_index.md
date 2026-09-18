---
title: series_groups property
second_title: Aspose.Slides dla Pythona poprzez .NET Referencję API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups właściwość
Zwraca grupy serii.
Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection).

### Uwagi

1) Każda grupa serii zawiera serie o łączonych typach. Grupy 
            łączonych typów serii definiowane i opisywane przy pomocy wyliczenia CombinableSeriesTypesGroup 
            enum.
            Ponadto każda grupa serii zawiera serie, które są rysowane albo 
            na osiach pierwotnych, albo na osiach wtórnych (nie oba przypadki w jednej grupie).
            Zatem zasada grupowania serii polega na grupowaniu według grup typów wymienionych 
            powyżej oraz według typu rysowania pierwotny/wtórny.

            2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla 
            każdej serii w grupie ("Series group properties").
            "Series group properties" w klasie ChartSeriesGroup jest odczyt/zapis.
            Każda z "Series group properties" może mieć projekcję tylko do odczytu w klasie ChartSeries.

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