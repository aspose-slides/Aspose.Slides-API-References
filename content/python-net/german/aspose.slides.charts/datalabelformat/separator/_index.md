---
title: separator property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator Eigenschaft
Legt fest oder gibt eine Variant zurück, die den Separator darstellt, der für die Datenbeschriftungen in einem Diagramm verwendet wird.
Lesen/Schreiben **str**.

### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat Objekt eine DataLabelCollection Sammlung von Datenbeschriftungen ist, dann bekommt oder setzt diese Eigenschaft den Standardwert der Separator Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection Sammlung.  
Setzt man diese Eigenschaft mit einem Wert, wird dieser Wert auch für die Separator Eigenschaft aller Datenbeschriftungen in der DataLabelCollection Sammlung festgelegt  
(z. B. "DataLabels.DefaultDataLabelFormat.Separator = val;" bewirkt, dass  
alle DataLabels[i].Separator den Wert val haben).

### Definition:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Siehe auch
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)