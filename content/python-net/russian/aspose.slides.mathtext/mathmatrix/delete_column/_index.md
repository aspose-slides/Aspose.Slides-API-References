---
title: delete_column method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Удаляет указанный столбец


```python
def delete_column(self, column_index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| column_index | **int** | Нулевой индекс столбца, который нужно удалить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Когда вы пытаетесь удалить последний единственный столбец в матрице |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Если columnIndex меньше нуля или больше либо равен ColumnCount |



### См. также
* класс [`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)