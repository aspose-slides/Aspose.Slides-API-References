---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Beállítja a külső munkafüzetet adatforrásként a diagramhoz. A diagram adatai a célmunkafüzetből frissülnek.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Path to the target workbook |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Beállítja a külső munkafüzetet adatforrásként a diagramhoz.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Path to the target workbook |
| update_chart_data | **bool** | Ha az érték hamis, csak a munkafüzet útvonala frissül. <br/><br/>             A diagram adatai nem lesznek betöltve és frissítve a célmunkafüzetből. Használható, ha a célmunkafüzet nem létezik vagy nem érhető el.<br/><br/>             Ha az érték igaz, a diagram adatai a célmunkafüzetből frissülnek. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |



### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)