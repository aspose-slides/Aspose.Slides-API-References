---
title: set_external_workbook method
second_title: Aspose.Slides for Python a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Beállítja a külső munkafüzetet adatforrásként a diagramhoz. A diagram adatai a célmunkafüzetből lesznek frissítve.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| workbook_path | **str** | A célmunkafüzet útvonala |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Beállítja a külső munkafüzetet adatforrásként a diagramhoz.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| workbook_path | **str** | A célmunkafüzet útvonala |
| update_chart_data | **bool** | If value is false only workbook path will be updated. <br/><br/>             Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available.<br/><br/>             If value is true chart data will be updated from the target workbook. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A külső munkafüzet nem érhető el, vagy nem tölthető be. |



### Lásd még
* class [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)