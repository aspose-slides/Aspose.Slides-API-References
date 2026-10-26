---
title: set_external_workbook method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы. Данные диаграммы будут обновлены из целевой рабочей книги.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевой рабочей книге |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешняя рабочая книга недоступна или не может быть загружена. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевой рабочей книге |
| update_chart_data | **bool** | Если значение false, будет обновлен только путь к рабочей книге. <br/><br/>             Данные диаграммы не будут загружаться и обновляться из целевой рабочей книги. Может быть использовано, когда целевая рабочая книга не существует или недоступна.<br/><br/>             Если значение true, данные диаграммы будут обновлены из целевой рабочей книги. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешняя рабочая книга недоступна или не может быть загружена. |



### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)