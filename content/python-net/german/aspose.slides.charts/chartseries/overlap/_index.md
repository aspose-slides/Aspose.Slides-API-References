---
title: overlap property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## Überlappungs Eigenschaft
Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100% bis 100%).
            Dies ist die Eigenschaft nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe.
            Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe, daher ist diese Eigenschaft schreibgeschützt.
            Um den Wert zu ändern, verwenden Sie die **ParentSeriesGroup.Overlap** Lese/Schreib-Eigenschaft.
            Nur-Lese **int**.

### Hinweise

Überlappung gibt den Grad der Überlappung oder des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an:
            - -100%: Maximaler Abstand (Balken sind vollständig getrennt).
            - 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.
            - 100%: Maximale Überlappung (Balken überlappen sich vollständig).
            Dies ist eine Projektion der Eigenschaft **ParentSeriesGroup.Overlap**.

### Definition:
```python
@property
def overlap(self):
    ...
```

### Siehe auch
* Klasse [`ChartSeries`](/slides/python-net/de/aspose.slides.charts/chartseries)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)