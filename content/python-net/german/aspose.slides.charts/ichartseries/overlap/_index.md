---
title: overlap property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## Overlap-Eigenschaft
Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100% bis 100%). 
Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe. 
Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe, sodass diese Eigenschaft schreibgeschützt ist.
Um den Wert zu ändern, verwenden Sie die Lese/Schreib-Eigenschaft ParentSeriesGroup.Overlap.
Schreibgeschützt **int**.

### Bemerkungen
Overlap gibt den Grad der Überlappung oder des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an:
- -100%: Maximale Abstände (Balken sind vollständig getrennt).
- 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
- 100%: Maximale Überlappung (Balken überlappen sich vollständig).
Dies ist eine Projektion der Eigenschaft ParentSeriesGroup.Overlap.

### Definition:
```python
@property
def overlap(self):
    ...
```

### Siehe auch
* Klasse [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)