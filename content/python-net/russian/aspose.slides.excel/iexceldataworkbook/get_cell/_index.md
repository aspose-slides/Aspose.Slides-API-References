---
title: get_cell method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Получает ячейку из указанного листа, используя его индекс и ссылку на ячейку в стиле Excel (например, "B2").

### Returns

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_index | **int** | Индекс листа, начинающийся с нуля. |
| cell_name | **str** | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Получает ячейку из указанного листа, используя ссылку на ячейку в стиле Excel (например, "B2").

### Returns

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
Получает ячейку из указанного листа, используя его индекс и координаты ячейки.

### Returns

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_index | **int** | Индекс листа, начинающийся с нуля. |
| row | **int** | Индекс строки ячейки, начинающийся с нуля. |
| column | **int** | Индекс столбца ячейки, начинающийся с нуля. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Получает ячейку из указанного листа, используя его имя и координаты ячейки.

### Returns

Ячейка в указанном месте.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| worksheet_name | **str** | Имя листа. |
| row | **int** | Индекс строки ячейки, начинающийся с нуля. |
| column | **int** | Индекс столбца ячейки, начинающийся с нуля. |



### See Also
* класс [`IExcelDataCell`](/slides/python-net/ru/aspose.slides.excel/iexceldatacell)
* класс [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook)
* модуль [`aspose.slides.excel`](/slides/python-net/ru/aspose.slides.excel)
* библиотека [`Aspose.Slides`](/slides/python-net)