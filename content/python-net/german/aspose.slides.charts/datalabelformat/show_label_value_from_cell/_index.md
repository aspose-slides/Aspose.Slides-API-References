---
title: show_label_value_from_cell property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell Eigenschaft
Stellt das Anzeigeverhalten des Zellwerts einer Datenbeschriftung eines angegebenen Diagramms dar.  
True zeigt den Zellwert an. False verbirgt ihn.  
Lesen/Schreiben **bool**.

### Anmerkungen
Wenn der übergeordnete Teil dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann bekommt bzw. setzt diese Eigenschaft den Standardwert der ShowLabelValueFromCell-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung.  
Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die ShowLabelValueFromCell-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" bewirkt, dass alle DataLabels[i].ShowLabelValueFromCell gleich val sind).

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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)