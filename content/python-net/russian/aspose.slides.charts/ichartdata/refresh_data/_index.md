---
title: refresh_data method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Обновляет данные диаграммы, перезагружая их из исходной рабочей книги.


```python
def refresh_data(self):
    ...
```


### Примечания

Если диаграмма использует внешнюю рабочую книгу, эта рабочая книга должна быть доступна во время вызова.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, когда формат рабочей книги не поддерживается, или когда [`IChartData.data_source_type`](/slides/python-net/ru/aspose.slides.charts/ichartdata/data_source_type) является<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ru/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) и внешняя рабочая книга не может быть доступна или загружена. |



### См. также
* класс [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)