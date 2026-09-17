---
title: add_table_from_workbook method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Получает таблицу из указанной книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

### Возвращаемое значение

Таблица, которая была добавлена в коллекцию фигур.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для размещения таблицы. |
| y | **float** | Координата Y для размещения таблицы. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook) | Книга Excel. |
| worksheet_name | **str** | Имя листа, содержащего таблицу. |
| cell_range | **str** | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр равен None или пуст, либо когда указанный лист или диапазон ячеек недействительны. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызывается, когда входные данные находятся в неподдерживаемом формате. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Получает таблицу из указанного файла книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

### Возвращаемое значение

Таблица, которая была добавлена в коллекцию фигур.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для размещения таблицы. |
| y | **float** | Координата Y для размещения таблицы. |
| workbook_path | **str** | Путь к файлу книги Excel. |
| worksheet_name | **str** | Имя листа, содержащего таблицу. |
| cell_range | **str** | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр равен None или пуст, либо когда указанный лист или диапазон ячеек недействительны. |
| **RuntimeError(Proxy error(IOException))** | Вызывается, когда при доступе к файлу книги происходит ошибка ввода-вывода. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызывается, когда входные данные находятся в неподдерживаемом формате. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Получает таблицу из указанного файла книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

### Возвращаемое значение

Таблица, которая была добавлена в коллекцию фигур.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для размещения таблицы. |
| y | **float** | Координата Y для размещения таблицы. |
| workbook_stream | **io.RawIOBase** | Поток, содержащий данные книги. |
| worksheet_name | **str** | Имя листа, содержащего таблицу. |
| cell_range | **str** | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр равен None или пуст, либо когда указанный лист или диапазон ячеек недействительны. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызывается, когда входные данные находятся в неподдерживаемом формате. |



### Смотрите также
* класс [`ExcelWorkbookImporter`](/slides/python-net/ru/aspose.slides.importing/excelworkbookimporter)
* класс [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`ITable`](/slides/python-net/ru/aspose.slides/itable)
* модуль [`aspose.slides.importing`](/slides/python-net/ru/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)