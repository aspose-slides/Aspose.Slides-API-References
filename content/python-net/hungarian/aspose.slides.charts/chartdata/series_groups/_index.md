---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups tulajdonság
Gets the groups of series.
Read-only [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection).

### Megjegyzések

1) Minden sorozatcsoport kombinálható típusokkal rendelkező sorozatokat tartalmaz. 
            A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum segítségével definiálják és írják le.
            Ezenkívül minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy elsődleges, vagy másodlagos tengelyeken vannak ábrázolva (nem mindkét eset egy csoportban).
            Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.
            
            2) A sorozatcsoport olyan sorozattulajdonságokat tartalmaz, amelyek közösek minden csoportbeli sorozatra ("series group properties").
            "Series group properties" in ChartSeriesGroup class is read/write.
            Each of "series group properties" can have a read-only projection in ChartSeries class.

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