---
title: insert_chart method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für Serien und Einstellungen und fügt es an der angegebenen Position in die Shape-Collection ein.

### Returns

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms in Punkt. |
| y | **float** | Die y-Koordinate des neuen Diagramms in Punkt. |
| width | **float** | Die Breite des neuen Diagramms in Punkt. |
| height | **float** | Die Höhe des neuen Diagramms in Punkt. |
| index | **int** | Der nullbasierte Index, an dem das neue Diagramm in die Shape-Collection eingefügt wird. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten für Serien und Einstellungen und fügt es an der angegebenen Position in die Shape-Collection ein.

### Returns

Das neu erstellte [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms in Punkt. |
| y | **float** | Die y-Koordinate des neuen Diagramms in Punkt. |
| width | **float** | Die Breite des neuen Diagramms in Punkt. |
| height | **float** | Die Höhe des neuen Diagramms in Punkt. |
| index | **int** | Der nullbasierte Index, an dem das neue Diagramm in die Shape-Collection eingefügt wird. |
| init_with_sample | **bool** | True, um das neue Diagramm mit Beispieldaten für Serien und Einstellungen zu initialisieren; <br/><br/>false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung beschleunigt. |



### See Also
* enumeration [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart)
* class [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)