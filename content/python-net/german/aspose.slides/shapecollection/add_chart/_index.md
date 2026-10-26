---
title: add_chart method
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für Serien und Einstellungen und fügt
            es am Ende der Formensammlung hinzu.

### Rückgabewert

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des Diagramms, in Punkten. |
| height | **float** | Die Höhe des Diagramms, in Punkten. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für Serien und Einstellungen und fügt
            es am Ende der Formensammlung hinzu.

### Rückgabewert

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des Diagramms, in Punkten. |
| height | **float** | Die Höhe des Diagramms, in Punkten. |
| init_with_sample | **bool** | True, um das neue Diagramm mit Beispieldaten für Serien und Einstellungen zu initialisieren; <br/><br/>            false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung<br/><br/>            beschleunigt. |



### Siehe auch
* Aufzählung [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype)
* Klasse [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)