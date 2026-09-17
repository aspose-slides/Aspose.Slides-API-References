---
title: add method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Добавить новую ячейку в коллекцию.

```python
def add(self, chart_data_cell):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) | Новая ячейка для добавления. |

## add(self, value) {#any}
Создаёт [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) из указанного значения и добавляет его в коллекцию.

```python
def add(self, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | **any** | Значение. |

### Примечания

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [`IChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/ichartdataworkbook) для добавления или изменения значений ячейки, убедитесь, что не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | если превышен лимит |

### См. также
* класс [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection)
* класс [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell)
* класс [`IChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/ichartdataworkbook)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)