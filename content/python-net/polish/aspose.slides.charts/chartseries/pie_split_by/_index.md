---
title: pie_split_by property
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by właściwość
Określa, jak ustalić, które punkty danych znajdują się w drugim plastrze lub słupku na wykresie typu pie-of-pie lub bar-of-pie.  
Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnych – jest to projekcja odpowiedniej właściwości grupy. W związku z tym właściwość ta jest tylko do odczytu.  
Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnych.  
Użyj właściwości ParentSeriesGroup.PieSplitBy (odczyt/zapis), aby zmienić wartość.  
Tylko do odczytu [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype).

### Uwagi

1) To jest projekcja własności ParentSeriesGroup.PieSplitBy.  
2) Jeśli wartość własności jest PieSplitType.Custom, możesz zdefiniować niestandardowe informacje o podziale przy użyciu własności ParentSeriesGroup.PieSplitCustomPoints.

### Definicja:
```python
@property
def pie_split_by(self):
    ...
```

### Zobacz także
* klasa [`ChartSeries`](/slides/python-net/pl/aspose.slides.charts/chartseries)
* enumeracja [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)