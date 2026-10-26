---
title: separator property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator property
Setzt oder gibt ein Variant zurück, das den separator darstellt, der für die Datenbeschriftungen in einem Diagramm verwendet wird.
Lesen/Schreiben **str**.


### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann bekommt diese property den Standardwert der Separator-property für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung. Setzt man diese property mit einem Wert, wird dieser Wert auch auf die Separator-property aller Datenbeschriftungen in der DataLabelCollection-Sammlung gesetzt (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to all DataLabels[i].Separator is equal to val).


### Definition:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Siehe Auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)