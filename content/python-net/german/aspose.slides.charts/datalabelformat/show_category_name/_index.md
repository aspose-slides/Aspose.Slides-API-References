---
title: show_category_name property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name Eigenschaft
Stellt das Anzeigeverhalten des Kategorienamens von Datenbeschriftungen eines angegebenen Diagramms dar.
True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn zu verbergen.
Lesen/Schreiben **bool**.

### Hinweise
Wenn der übergeordnete DataLabelFormat-Objekt ein DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann holt oder setzt diese Eigenschaft den Standardwert der ShowCategoryName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung.
Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowCategoryName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung (z. B. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" bewirkt, dass alle DataLabels[i].ShowCategoryName gleich val sind).

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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)