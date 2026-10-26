---
title: series_groups property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups tulajdonság
Lekéri a sorozatok csoportjait.
            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection).


### Megjegyzések

1) Minden sorozatcsoport kombinálható típusú sorozatokat tartalmaz. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum határozza meg és írja le.
            Ezenkívül minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy az elsődleges tengelyen, vagy a másodlagos tengelyen kerülnek ábrázolásra (nem mindkét eset egyszerre egy csoportban).
            Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.

            2) A sorozatcsoport tartalmaz néhány sorozati tulajdonságot, amelyek közösek a csoport minden sorozatára („series group properties”).
            „Series group properties” a ChartSeriesGroup osztályban olvasható/írható.
            A „series group properties” egy-egy eleme csak olvasható projekcióval rendelkezhet a ChartSeries osztályban.

### Definíció:
```python
@property
def series_groups(self):
    ...
```


### Lásd még
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* osztály [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)