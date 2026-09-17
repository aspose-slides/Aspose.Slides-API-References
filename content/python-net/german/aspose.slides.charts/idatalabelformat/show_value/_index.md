---
title: show_value property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value Eigenschaft
Stellt das Anzeigeverhalten des Prozentwerts der Datenbeschriftung eines bestimmten Diagramms dar. 
            True zeigt den Prozentwert an. False versteckt ihn.
            Lesen/Schreiben **bool**.


### Anmerkungen

Wenn der übergeordnete DataLabelFormat-Objekt eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann
            Eigenschaft erhält oder setzt den Standardwert der ShowValue Eigenschaft für die neuen Daten
            Beschriftungen in der DataLabelCollection-Sammlung.
            Setze diese Eigenschaft mit einem Wert, setzt diesen Wert auch auf die ShowValue Eigenschaft 
            für alle Datenbeschriftungen in der DataLabelCollection-Sammlung
            (z. B. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" führt zu 
            dass alle DataLabels[i].ShowValue gleich val ist).


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
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)