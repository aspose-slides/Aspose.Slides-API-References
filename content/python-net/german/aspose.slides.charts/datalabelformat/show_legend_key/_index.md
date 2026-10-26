---
title: show_legend_key property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key Eigenschaft
Stellt das Anzeigeverhalten des Legende-Schlüssels einer Datenbeschriftung eines angegebenen Diagramms dar. 
            True, wenn das Datenbeschriftungs-Legendsymbol sichtbar ist.
            Lesen/Schreiben **bool**.


### Bemerkungen
Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann
            ruft diese Eigenschaft den Standardwert der ShowLegendKey-Eigenschaft für die neuen Daten 
            Beschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest.
Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowLegendKey-Eigenschaft 
            aller Datenbeschriftungen in der DataLabelCollection-Sammlung festgelegt
            (z. B. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" bewirkt, dass 
            alle DataLabels[i].ShowLegendKey gleich val sind).


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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)