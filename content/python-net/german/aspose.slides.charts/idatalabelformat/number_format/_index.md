---
title: number_format property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format Eigenschaft
Stellt die Formatzeichenfolge für das DataLabels-Objekt dar.
            Lesen/Schreiben **str**.


### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der NumberFormat-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest.
            Wenn diese Eigenschaft mit einem Wert gesetzt wird, wird dieser Wert auch für die NumberFormat-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt (z. B. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" bewirkt, dass alle DataLabels[i].NumberFormat den Wert val erhalten).

### Definition:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)