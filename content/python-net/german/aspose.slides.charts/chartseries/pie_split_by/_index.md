---
title: pie_split_by property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by Eigenschaft
Specifiziert, wie bestimmt wird, welche Datenpunkte sich im zweiten Kuchen oder Balken 
            in einem pie-of-pie- oder bar-of-pie-Diagramm befinden.
            Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe 
            – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Und daher ist diese Eigenschaft 
            schreibgeschützt.
            Verwenden Sie die ParentSeriesGroup Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen.
            Verwenden Sie die ParentSeriesGroup.PieSplitBy Lese-/Schreib-Eigenschaft, um den Wert zu ändern.
            Schreibgeschützt [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype).


### Bemerkungen

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy.
            2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Split-Informationen mit der ParentSeriesGroup.PieSplitCustomPoints-Eigenschaft definieren.

### Definition:
```python
@property
def pie_split_by(self):
    ...
```


### Siehe auch
* Klasse [`ChartSeries`](/slides/python-net/de/aspose.slides.charts/chartseries)
* Aufzählung [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)