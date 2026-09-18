---
title: set_external_workbook method
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Külső munkafüzetet állít be adatforrásként a diagramhoz. A diagram adatai a célmunkafüzetből frissülnek.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| workbook_path | **str** | A célmunkafüzet elérési útja |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Külső munkafüzetet állít be adatforrásként a diagramhoz.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| workbook_path | **str** | A célmunkafüzet elérési útja |
| update_chart_data | **bool** | Ha az érték hamis, csak a munkafüzet útvonala frissül. <br/><br/>             A diagram adatai nem lesznek betöltve és frissítve a célmunkafüzetből. Akkor használható, ha a célmunkafüzet nem létezik vagy nem érhető el.<br/><br/>             Ha az érték igaz, a diagram adatai frissülnek a célmunkafüzetből. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |



### Lásd még
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)