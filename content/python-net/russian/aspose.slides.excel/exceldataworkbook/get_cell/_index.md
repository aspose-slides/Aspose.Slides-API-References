---
title: get_cell method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Получает ячейку из указанного листа, используя её индекс и имя ячейки в стиле Excel (например, "B2").

### Возвращаемое значение

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_index | **int** | Нулевой индекс листа. |
| cell_name | **str** | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Получает ячейку из указанного листа, используя имя ячейки в стиле Excel (например, "B2").

### Возвращаемое значение

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_name | **str** | Имя листа. |
| cell_name | **str** | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Получает ячейку из указанного листа, используя её индекс и координаты ячейки.

### Возвращаемое значение

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_index | **int** | Нулевой индекс листа. |
| row | **int** | Нулевой индекс строки ячейки. |
| column | **int** | Нулевой индекс столбца ячейки. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Получает ячейку из указанного листа, используя его имя и координаты ячейки.

### Возвращаемое значение

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_name | **str** | Имя листа. |
| row | **int** | Нулевой индекс строки ячейки. |
| column | **int** | Нулевой индекс столбца ячейки. |



### См. также
* класс [`ExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook)
* класс [`IExcelDataCell`](/slides/python-net/ru/aspose.slides.excel/iexceldatacell)
* модуль [`aspose.slides.excel`](/slides/python-net/ru/aspose.slides.excel)
* библиотека [`Aspose.Slides`](/slides/python-net)