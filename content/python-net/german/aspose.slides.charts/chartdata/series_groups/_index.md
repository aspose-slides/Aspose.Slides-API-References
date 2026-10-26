---
title: series_groups property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups Eigenschaft
Ruft die Gruppen von Serien ab.
            Nur lesbar [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection).


### Hinweise

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von 
            kombinierbaren Serientypen werden mit dem Enum CombinableSeriesTypesGroup 
            definiert und beschrieben.
            Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen 
            oder auf sekundären Achsen dargestellt werden (nicht beide Fälle in einer Gruppe).
            Das Prinzip der Seriensortierung besteht also darin, nach den oben genannten 
            Typgruppen und nach dem primären/sekundären Darstellungstyp zu gruppieren.
            
            2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie 
            in der Gruppe gemeinsam sind ("series group properties").
            "series group properties" in der Klasse ChartSeriesGroup ist Lese-/Schreibzugriff.
            Jede "series group properties" kann eine Nur lesbar-Projektion in der Klasse ChartSeries haben.

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