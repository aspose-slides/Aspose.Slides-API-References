---
title: delete_row method
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Удаляет указанную строку


```python
def delete_row(self, row_index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| row_index | **int** | Нулевой индекс строки, которую нужно удалить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Когда вы пытаетесь удалить последнюю единственную строку в матрице |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Если rowIndex меньше нуля или больше либо равен RowCount |



### Смотрите также
* класс [`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)