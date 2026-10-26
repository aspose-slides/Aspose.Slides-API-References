---
title: show_percentage property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage Eigenschaft
Stellt das Anzeigeverhalten des prozentualen Wertes einer Datenbeschriftung eines angegebenen Diagramms dar. 
            True zeigt den Prozentwert an. False verbirgt ihn.
            Lesen/Schreiben **bool**.

### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection Sammlung von Datenbeschriftungen ist, dann bekommt oder setzt diese Eigenschaft den Standardwert der ShowPercentage Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection Sammlung. 
            Setzt man diese Eigenschaft mit einem Wert, wird dieser Wert ebenfalls auf die ShowPercentage Eigenschaft aller Datenbeschriftungen in der DataLabelCollection Sammlung gesetzt (z.B. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" bewirkt, dass alle DataLabels[i].ShowPercentage gleich val ist).

### Definition:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)