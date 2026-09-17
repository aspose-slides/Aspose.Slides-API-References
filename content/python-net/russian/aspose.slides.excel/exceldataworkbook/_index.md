---
title: ExcelDataWorkbook class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook класс

Представляет книгу, предоставляющую доступ к данным Excel для общего использования.

Тип ExcelDataWorkbook содержит следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/__init__/#str) | Инициализирует новый экземпляр, используя указанный путь к файлу. |
| [`__init__(self, stream)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Инициализирует новый экземпляр класса, используя предоставленный поток. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Получает ячейку из указанного листа, используя её индекс и координаты ячейки. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Получает ячейку из указанного листа, используя её имя и координаты ячейки. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Получает ячейку из указанного листа, используя её индекс и имя ячейки в стиле Excel (например, "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Получает ячейку из указанного листа, используя имя ячейки в стиле Excel (например, "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Получает коллекцию ячеек из книги, соответствующих указанной формуле. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Получает словарь, содержащий индексы и имена всех диаграмм в указанном листе книги Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/ru/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Получает имена всех листов, содержащихся в книге Excel. |

### См. также
* модуль [`aspose.slides.excel`](/slides/python-net/ru/aspose.slides.excel)
* библиотека [`Aspose.Slides`](/slides/python-net)