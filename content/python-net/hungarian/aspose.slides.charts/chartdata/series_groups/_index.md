---
title: series_groups property
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups tulajdonság
Lekéri a sorozatok csoportjait.
            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection).

### Megjegyzések

1) Minden sorozatcsoport kombinálható típusú sorozatokat tartalmaz. A kombinálható sorozattípusok csoportjai a CombinableSeriesTypesGroup enumerációval vannak definiálva és leírva.
            Továbbá minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek elsődleges vagy másodlagos tengelyen vannak ábrázolva (nem mindkét eset egy csoportban).
            Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.

2) A sorozatcsoport olyan sorozattulajdonságokat tartalmaz, amelyek közösek a csoport minden sorozata számára ("Series group properties").
            "Series group properties" a ChartSeriesGroup osztályban olvasható/írható.
            "Series group properties" mindegyike rendelkezhet egy csak olvasható projekcióval a ChartSeries osztályban.

### Definíció:
```python
@property
def series_groups(self):
    ...
```

### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* osztály [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)