---
title: add method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Если категория существует в коллекции, вернуть её. Иначе создаёт новую категорию диаграммы из
[`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) и добавляет её в коллекцию.

### Возвращаемое значение

Добавленная или существующая категория.



```python
def add(self, chart_data_cell):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) | Ячейка, используемая для создания категории диаграммы. |


## add(self, value) {#any}
Создаёт новый [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory) из значения и добавляет его в коллекцию.

### Возвращаемое значение

Добавлен [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| value | **any** | Значение. |

### Замечания

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [`ChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/chartdataworkbook) для добавления или редактирования значений ячеек, убедитесь, что не используете этот лист.
Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | если превышен лимит |



### См. также
* класс [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory)
* класс [`ChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection)
* класс [`ChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/chartdataworkbook)
* класс [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory)
* класс [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)