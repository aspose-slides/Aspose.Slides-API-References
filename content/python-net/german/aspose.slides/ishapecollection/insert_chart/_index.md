---
title: insert_chart method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen,
            und fügt es an der angegebenen Position in die Formsammlung ein.

### Rückgabewert

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der zu erstellende Diagrammtyp. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int** | Der nullbasierte Index, an dem das neue Diagramm in die Formsammlung eingefügt wird. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen,
            und fügt es an der angegebenen Position in die Formsammlung ein.

### Rückgabewert

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der zu erstellende Diagrammtyp. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int** | Der nullbasierte Index, an dem das neue Diagramm in die Formsammlung eingefügt wird. |
| init_with_sample | **bool** | True, um das neue Diagramm mit Beispieldaten und -einstellungen zu initialisieren; <br/><br/>            false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, wodurch die Erstellung schneller ist. |


### Siehe auch
* Aufzählung [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype)
* Klasse [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)