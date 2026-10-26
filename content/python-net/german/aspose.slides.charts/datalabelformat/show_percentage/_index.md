---
title: show_percentage property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage Eigenschaft
Stellt das Anzeigeverhalten des Prozentwerts einer Datenbeschriftung eines angegebenen Diagramms dar. 
True zeigt den Prozentwert an. False verbirgt ihn.
Lesen/Schreiben **bool**.


### Anmerkungen

Wenn der übergeordnete Parameter dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowPercentage-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest.
Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert auch für die ShowPercentage-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung fest.
(z. B. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" bewirkt, dass alle DataLabels[i].ShowPercentage gleich val sind.)

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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)