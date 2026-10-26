---
title: pie_split_by property
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by tulajdonság
Megadja, hogyan kell meghatározni, mely adatpontok vannak a második szeletben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon.
Ez a tulajdonság nem csak ehhez a sorozathoz tartozik, hanem a szülő sorozatcsoport összes sorozatához – ez a megfelelő csoporttulajdonság projekciója.
Ezért ez a tulajdonság csak olvasható.
Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez.
Használja a ParentSeriesGroup.PieSplitBy olvasás/írás tulajdonságot az érték módosításához.
Csak olvasható [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype).

### Megjegyzések

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója.
2) Ha a tulajdonság értéke PieSplitType.Custom, akkor egyedi felosztási információt határozhat meg a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal.

### Definíció:
```python
@property
def pie_split_by(self):
    ...
```

### Lásd még
* osztály [`ChartSeries`](/slides/python-net/hu/aspose.slides.charts/chartseries)
* enumeráció [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)