---
title: refresh_data method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Обновляет данные диаграммы, заново загружая их из исходной рабочей книги.


```python
def refresh_data(self):
    ...
```


### Примечания

Если диаграмма использует внешнюю рабочую книгу, она должна быть доступна во время вызова.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выброшено, когда формат рабочей книги не поддерживается, или когда [`ChartData.data_source_type`](/slides/python-net/ru/aspose.slides.charts/chartdata/data_source_type)<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ru/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) и внешняя рабочая книга недоступна или не может быть загружена. |



### См. также
* класс [`ChartData`](/slides/python-net/ru/aspose.slides.charts/chartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)