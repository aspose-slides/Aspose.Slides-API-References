---
title: show_bubble_size property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size Eigenschaft
Stellt das Anzeigeverhalten des Bubble-Size-Werts eines angegebenen Diagramms dar.  
True zeigt den Bubble-Size-Wert an. False versteckt ihn.  
Lesen/Schreiben **bool**.


### Bemerkungen

Wenn das übergeordnete Objekt dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann bekommt oder setzt diese
Eigenschaft den Standardwert der ShowBubbleSize-Eigenschaft für die neuen Daten
beschriftungen in der DataLabelCollection-Sammlung.  
Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowBubbleSize-Eigenschaft
aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt  
(i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" bewirkt, dass
alle DataLabels[i].ShowBubbleSize gleich val ist).


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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)