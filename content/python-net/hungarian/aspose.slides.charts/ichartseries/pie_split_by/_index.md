---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by tulajdonság
Meghatározza, hogyan kell meghatározni, mely adatok találhatók a második kör vagy sáv 
            egy kör-kör vagy sáv-kör diagramon.
            Ez a tulajdonság nem csak ennél a sorozatnál, hanem az összes szülő sorozati 
            csoport sorozatánál érvényes – ez a megfelelő csoport tulajdonságának projekciója. Így ez a tulajdonság 
            csak olvasható.
            Használja a ParentSeriesGroup tulajdonságot a szülő sorozati csoport eléréséhez.
            Használja a ParentSeriesGroup.PieSplitBy olvasás/írás tulajdonságot az érték módosításához.
            Csak olvasható [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype).


### Megjegyzések

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója.
            2) Ha a tulajdonság értéke PieSplitType.Custom, akkor egyéni felosztási 
            információt adhat meg a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal.

### Definíció:
```python
@property
def pie_split_by(self):
    ...
```


### Lásd még
* osztály [`IChartSeries`](/slides/python-net/hu/aspose.slides.charts/ichartseries)
* felsorolás [`PieSplitType`](/slides/python-net/hu/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)