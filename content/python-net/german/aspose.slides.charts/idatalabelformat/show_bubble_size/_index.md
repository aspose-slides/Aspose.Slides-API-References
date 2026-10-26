---
title: show_bubble_size property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size Eigenschaft
Stellt das Anzeigeverhalten des Bubble-Größenwerts eines bestimmten Diagramms für das Datenbeschriftungs-Label dar. 
            True zeigt den Bubble-Größenwert an. False blendet ihn aus.
            Lesen/Schreiben **bool**.


### Anmerkungen

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese
            Eigenschaft den Standardwert der ShowBubbleSize-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest.
            Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert ebenfalls für die ShowBubbleSize-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung fest (z. B. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" bewirkt, dass alle DataLabels[i].ShowBubbleSize den Wert val haben).


### Definition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)