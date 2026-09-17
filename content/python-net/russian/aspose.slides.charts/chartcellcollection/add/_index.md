---
title: add method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Добавить новую ячейку в коллекцию.

```python
def add(self, cell):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) | Новая ячейка для добавления. |

## add(self, value) {#any}
Создаёт [`ChartDataCell`](/slides/python-net/ru/aspose.slides.charts/chartdatacell) из указанного значения и добавляет его в коллекцию.

```python
def add(self, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | **any** | Значение. |

### Примечания

Этот метод добавляет лист с именем AUTO_DATA и добавляет все значения туда.  Если вы используете [`ChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/chartdataworkbook) для добавления или изменения значений Cell, убедитесь, что вы не используете этот лист
            Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | если превышен предел |



### См. также
* класс [`ChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/chartcellcollection)
* класс [`ChartDataCell`](/slides/python-net/ru/aspose.slides.charts/chartdatacell)
* класс [`ChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/chartdataworkbook)
* класс [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)