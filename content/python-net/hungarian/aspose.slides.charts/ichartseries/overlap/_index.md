---
title: overlap property
second_title: Aspose.Slides Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## átfedés tulajdonság
Megadja, hogy a sávok és oszlopok mennyire fednek át 2-D diagramokon, százalékban (-100% és 100% között). 
            Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes. 
            Ez a szülő sorozatcsoport megfelelő tulajdonságának projekciója, ezért ez a tulajdonság csak olvasható.
            Az érték módosításához használja a ParentSeriesGroup.Overlap olvasható/írható tulajdonságot.
            Csak olvasható **int**.

### Megjegyzések

Átfedés megadja az átfedés vagy távolság mértékét a sávok és oszlopok között, százalékban a szélességükhöz képest:
            - -100%: Maximális távolság (a sávok teljesen el vannak választva).
            - 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
            - 100%: Maximális átfedés (a sávok teljesen átfedik egymást).
            Ez a ParentSeriesGroup.Overlap tulajdonság projekciója.

### Definíció:
```python
@property
def overlap(self):
    ...
```

### Lásd még
* osztály [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)