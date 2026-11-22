---
title: set_external_workbook method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Устанавливает внешний рабочий лист в качестве источника данных для диаграммы. Данные диаграммы будут обновлены из целевого рабочего листа.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевому рабочему листу |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешний рабочий лист недоступен или не может быть загружен. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Устанавливает внешний рабочий лист в качестве источника данных для диаграммы.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| workbook_path | **str** | Путь к целевому рабочему листу |
| update_chart_data | **bool** | Если значение ложно, будет обновлен только путь к рабочему листу. <br/><br/> Данные диаграммы не будут загружаться и обновляться из целевого рабочего листа. Может использоваться, когда целевой рабочий лист не существует или недоступен.<br/><br/> Если значение истинно, данные диаграммы будут обновлены из целевого рабочего листа. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Внешний рабочий лист недоступен или не может быть загружен. |



### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)