---
title: show_legend_key property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key Eigenschaft
Stellt das Anzeigeverhalten des Legenden-Schlüssels der Datenbeschriftung eines angegebenen Diagramms dar.  
True, wenn der Legenden-Schlüssel der Datenbeschriftung sichtbar ist.  
Lesen/Schreiben **bool**.

### Bemerkungen

Wenn der übergeordnete Teil dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder setzt ihn.  
Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowLegendKey-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" führt dazu, dass alle DataLabels[i].ShowLegendKey gleich val sind).

### Definition:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)