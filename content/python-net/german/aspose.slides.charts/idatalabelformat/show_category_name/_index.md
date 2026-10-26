---
title: show_category_name property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name Eigenschaft
Stellt das Anzeigeverhalten des Kategorienamens der Datenbeschriftung eines bestimmten Diagramms dar.
True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen.
Lesen/Schreiben **bool**.

### Hinweise

Wenn das übergeordnete Objekt dieses DataLabelFormat-Objekts eine DataLabelCollection Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowCategoryName Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection Sammlung ab oder setzt ihn.
Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert außerdem für die ShowCategoryName Eigenschaft aller Datenbeschriftungen in der DataLabelCollection Sammlung fest.
(z.B. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" bewirkt, dass all DataLabels[i].ShowCategoryName gleich val ist).

### Definition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)