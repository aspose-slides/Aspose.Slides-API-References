---
title: show_series_name property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name Eigenschaft
Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. 
            True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen.
            Lese/Schreib **bool**.


### Hinweise

Wenn der übergeordnete Objekt dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann ruft diese Eigenschaft den Standardwert der ShowSeriesName-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft mit einem Wert legt diesen Wert ebenfalls für die ShowSeriesName-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung fest (d. h. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" führt dazu, dass alle DataLabels[i].ShowSeriesName gleich val ist).

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Siehe auch
* Klasse [`IDataLabelFormat`](/slides/python-net/de/aspose.slides.charts/idatalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)