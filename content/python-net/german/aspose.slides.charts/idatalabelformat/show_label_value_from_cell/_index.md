---
title: show_label_value_from_cell property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell Eigenschaft
Stellt das Anzeigeverhalten des Zellenwerts von Datenbeschriftungen eines angegebenen Diagramms dar. 
True zeigt den Zellenwert an. False verbirgt ihn. 
Lesen/Schreiben **bool**.

### Hinweise

Wenn der übergeordnete Container dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann
            Eigenschaft gibt den Standardwert der ShowLabelValueFromCell Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung zurück oder setzt ihn.
            Setzt diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowLabelValueFromCell Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung übernommen
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" bewirkt,
            dass alle DataLabels[i].ShowLabelValueFromCell gleich val sind).

### Definition:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)