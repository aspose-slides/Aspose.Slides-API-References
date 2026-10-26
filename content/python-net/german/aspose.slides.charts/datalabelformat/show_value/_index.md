---
title: show_value property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value Eigenschaft
Stellt das Anzeigeverhalten des prozentualen Werts einer Datenbeschriftung eines angegebenen Diagramms dar.
            True zeigt den Prozentwert an. False verbirgt ihn.
            Lesen/Schreiben **bool**.

### Hinweise
Wenn der übergeordnete Block dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann diese
            Eigenschaft ruft den Standardwert der ShowValue-Eigenschaft für die neuen Daten 
            Beschriftungen in der DataLabelCollection-Sammlung.
            Setzt diese Eigenschaft mit einem Wert, wird dieser Wert ebenfalls für die ShowValue-Eigenschaft 
            aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt
            (z. B. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" bewirkt, dass 
            alle DataLabels[i].ShowValue den Wert val haben).

### Definition:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Siehe auch
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)