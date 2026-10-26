---
title: show_series_name property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name Eigenschaft
Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzuzeigen. 
            True, um den Seriennamen anzuzeigen. False, um ihn zu verbergen.
            Lesen/Schreiben **bool**.


### Hinweise

Wenn das übergeordnete Element dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, dann
            Eigenschaft liest oder schreibt den Standardwert der ShowSeriesName-Eigenschaft für die neuen Daten 
            Beschriftungen in der DataLabelCollection-Sammlung.
            Setzen Sie diese Eigenschaft mit einem Wert, setzt diesen Wert auch für die ShowSeriesName-Eigenschaft 
            für alle Datenbeschriftungen in der DataLabelCollection-Sammlung
            (z. B. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" führt dazu, dass 
            alle DataLabels[i].ShowSeriesName den Wert val haben).

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
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)