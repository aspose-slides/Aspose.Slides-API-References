---
title: series_groups property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups Eigenschaft
Liefert die Gruppen von Serien.
            Nur-Lesen [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection).


### Hinweise

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von 
            kombinierbaren Serientypen, definiert und beschrieben mit CombinableSeriesTypesGroup 
            enum.
            Außerdem enthält jede Gruppe von Serien Serien, die entweder 
            auf primären Achsen oder auf sekundären Achsen (nicht beide Fälle in einer Gruppe).
            So ist das Prinzip der Seriengruppierung eine Gruppierung nach den erwähnten Typgruppen 
            oben und nach primärem/sekundärem Plottyp.
            
            2) Gruppe von Serien enthält einige Serieneigenschaften, die für 
            jede Serie in der Gruppe gemeinsam sind ("series group properties").
            "Series group properties" in ChartSeriesGroup class ist Lesen/Schreiben.
            Jede "series group properties" kann eine Nur-Lesen-Projektion in ChartSeries class haben.

### Definition:
```python
@property
def series_groups(self):
    ...
```


### Siehe auch
* Klasse [`ChartData`](/slides/python-net/de/aspose.slides.charts/chartdata)
* Klasse [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)