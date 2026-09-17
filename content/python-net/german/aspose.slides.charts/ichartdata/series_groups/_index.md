---
title: series_groups property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups Eigenschaft
Gibt die Gruppen von Serien zurück.
Nur lesbar [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection).

### Anmerkungen

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Daher basiert das Prinzip der Seriendefinition auf einer Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp.

2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("series group properties").
"Series group properties" in der Klasse ChartSeriesGroup ist Lesen/Schreiben.
Jede der "series group properties" kann eine Nur lesbare Projektion in der Klasse ChartSeries haben.

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