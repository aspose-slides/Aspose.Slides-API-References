---
title: series_groups property
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups właściwość
Pobiera grupy serii.
            Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection).

### Uwagi

1) Każda grupa serii zawiera serie o łączonych typach.
            Grupy łączonych typów serii są definiowane i opisywane przy pomocy wyliczenia CombinableSeriesTypesGroup 
            enum.
            Ponadto każda grupa serii zawiera serie, które są wykreślane albo na głównych osiach, albo na drugorzędnych osiach (nie oba przypadki w jednej grupie).
            Zatem zasada grupowania serii polega na grupowaniu według wymienionych wcześniej grup typów oraz według typu wykreślania (główny/drugorzędny).
            
            2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”).
            „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis.
            Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

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