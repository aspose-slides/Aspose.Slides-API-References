---
title: series_groups property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups Eigenschaft
Liefert die Gruppen von Serien.
            Nur lesbar [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection).


### Bemerkungen

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von 
            kombinierbaren Serientypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. 
            Auch enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen dargestellt werden (nicht beide Fälle in einer Gruppe). 
            Daher basiert das Prinzip der Seriengruppierung auf einer Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Darstellungstyp.
            
            2) Eine Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("series group properties").
            Die "Series group properties" in der Klasse ChartSeriesGroup ist lesbar/schreibbar.
            Jede der "series group properties" kann in der Klasse ChartSeries eine Nur-lesbar-Abbildung haben.

### Definition:
```python
@property
def series_groups(self):
    ...
```


### Siehe auch
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Klasse [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)