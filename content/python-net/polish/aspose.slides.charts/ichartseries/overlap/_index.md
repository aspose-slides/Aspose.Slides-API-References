---
title: overlap property
second_title: Aspose.Slides dla Pythona przy użyciu .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap właściwość
Określa, jak bardzo słupki i kolumny nachodzą na siebie w wykresach 2-D, wyrażone jako procent (od -100% do 100%). 
            Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej. 
            Jest to projekcja odpowiedniej właściwości w grupie serii nadrzędnych, dlatego ta właściwość jest tylko do odczytu.
            Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap do odczytu/zapisu.
            Tylko do odczytu **int**.


### Uwagi

Overlap określa stopień nachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
            - -100%: Maksymalny odstęp (słupki są całkowicie oddzielone).
            - 0%: Słupki są ustawione obok siebie bez nachodzenia ani odstępu.
            - 100%: Maksymalne nachodzenie (słupki całkowicie nachodzą na siebie).
            Jest to projekcja właściwości ParentSeriesGroup.Overlap.

### Definicja:
```python
@property
def overlap(self):
    ...
```


### Zobacz także
* klasa [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)