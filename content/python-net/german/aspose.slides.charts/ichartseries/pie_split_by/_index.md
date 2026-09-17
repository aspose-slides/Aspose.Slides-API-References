---
title: pie_split_by property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by Eigenschaft
Gibt an, wie bestimmt wird, welche Datenpunkte sich im zweiten Kuchen oder Balken eines Kuchen-in-Kuchen- oder Balken-in-Kuchen-Diagramms befinden.  
Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe - dies ist die Projektion der entsprechenden Gruppeneigenschaft. Und so ist diese Eigenschaft schreibgeschützt.  
Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen.  
Verwenden Sie die ParentSeriesGroup.PieSplitBy Lese/Schreib-Eigenschaft, um den Wert zu ändern.  
Schreibgeschützt [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype).


### Hinweise

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy.  
2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Aufteilunginformationen mit der ParentSeriesGroup.PieSplitCustomPoints-Eigenschaft definieren.

### Definition:
```python
@property
def pie_split_by(self):
    ...
```


### Siehe auch
* Klasse [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries)
* Aufzählung [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)