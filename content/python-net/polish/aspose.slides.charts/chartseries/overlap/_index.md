---
title: overlap property
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap właściwość
Określa, jak bardzo słupki i kolumny zachodzą na siebie na wykresach 2-D, wyrażone jako procent (od -100% do 100%). 
            Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej. 
            Jest to projekcja odpowiedniej właściwości w grupie serii nadrzędnej, dlatego ta właściwość jest tylko do odczytu.
            Aby zmienić wartość, użyj właściwości **ParentSeriesGroup.Overlap** do odczytu/zapisu.
            Tylko do odczytu **int**.


### Uwagi

Overlap określa stopień zachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
            - -100%: Maksymalny odstęp (słupki są całkowicie oddzielone).
            - 0%: Słupki są umieszczone obok siebie bez zachodzenia ani odstępu.
            - 100%: Maksymalne zachodzenie (słupki całkowicie zachodzą na siebie).
            Jest to projekcja właściwości **ParentSeriesGroup.Overlap**.

### Definicja:
```python
@property
def overlap(self):
    ...
```


### Zobacz także
* klasa [`ChartSeries`](/slides/python-net/pl/aspose.slides.charts/chartseries)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)