---
title: series_groups property
second_title: Aspose.Slides a Pythonhoz a .NET API-re vonatkozó hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups tulajdonság
Lekéri a sorozatok csoportjait.
            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection).

### Megjegyzések

1) Minden sorozatcsoport kombinálható típusú sorozatokat tartalmaz. A kombinálható sorozattípusok csoportjai a **CombinableSeriesTypesGroup** enum-ban vannak definiálva és leírva. Továbbá minden sorozatcsoport sorozatot tartalmaz, amely vagy az elsődleges tengelyeken, vagy a másodlagos tengelyeken kerül ábrázolásra (nem mindkét eset egyszerre egy csoportban). Így a sorozatcsoportosítás szabálya a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.

2) A sorozatcsoport néhány olyan sorozat-tulajdonságot tartalmaz, amely a csoport minden sorozatára közös („sorozatcsoport tulajdonságok”). A **ChartSeriesGroup** osztályban a „sorozatcsoport tulajdonságok” olvasás-írás engedéllyel rendelkeznek. Minden „sorozatcsoport tulajdonság” egy csak-olvasható leképezést kaphat a **ChartSeries** osztályban.

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