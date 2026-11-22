---
title: set_external_workbook method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Устанавливает внешнюю книгу как источник данных для диаграммы. Данные диаграммы будут обновляться из целевой книги.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевой книге |

### Exceptions

| Exception | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешняя книга недоступна или не может быть загружена. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Устанавливает внешнюю книгу как источник данных для диаграммы.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевой книге |
| update_chart_data | **bool** | Если значение равно false, будет обновлен только путь к книге. <br/><br/>             Данные диаграммы не будут загружаться и обновляться из целевой книги. Может использоваться, когда целевая книга не существует или недоступна.<br/><br/>             Если значение равно true, данные диаграммы будут обновлены из целевой книги. |

### Exceptions

| Exception | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешняя книга недоступна или не может быть загружена. |



### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)