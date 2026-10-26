---
title: add_chart_from_workbook method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Получает диаграмму из указанной рабочей книги Excel и добавляет её в конец указанной коллекции фигур в заданных координатах.

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для позиционирования диаграммы. |
| y | **float** | Координата Y для позиционирования диаграммы. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook) | Рабочая книга Excel. |
| worksheet_name | **str** | Имя листа, содержащего диаграмму. |
| chart_index | **int** | Нулевой индекс диаграммы, которую нужно вставить. <br/><br/>            Этот индекс можно получить с помощью метода **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Если `true`, в диаграмму будет встроена вся рабочая книга; <br/><br/>            если `false`, будут встроены только данные диаграммы. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр имеет значение None, пустой, или когда диаграмму невозможно найти в рабочей книге. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Получает диаграмму из указанной рабочей книги Excel и добавляет её в конец указанной коллекции фигур в заданных координатах.

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для позиционирования диаграммы. |
| y | **float** | Координата Y для позиционирования диаграммы. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook) | Рабочая книга Excel. |
| worksheet_name | **str** | Имя листа, содержащего диаграмму. |
| chart_name | **str** | Имя диаграммы, которую нужно добавить. |
| embed_all_workbook | **bool** | Если `true`, в диаграмму будет встроена вся рабочая книга; <br/><br/>            если `false`, будут встроены только данные диаграммы. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр имеет значение None, пустой, или когда диаграмму невозможно найти в рабочей книге. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Получает диаграмму из указанной рабочей книги Excel и добавляет её в конец указанной коллекции фигур в заданных координатах.

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для позиционирования диаграммы. |
| y | **float** | Координата Y для позиционирования диаграммы. |
| workbook_stream | **io.RawIOBase** | Поток, содержащий данные рабочей книги. |
| worksheet_name | **str** | Имя листа, содержащего диаграмму. |
| chart_name | **str** | Имя диаграммы, которую нужно добавить. |
| embed_all_workbook | **bool** | Если `true`, в диаграмму будет встроена вся рабочая книга; <br/><br/>            если `false`, будут встроены только данные диаграммы. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр имеет значение None, пустой, или когда диаграмму невозможно найти в рабочей книге. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызывается, когда входные данные имеют неподдерживаемый формат. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Получает диаграмму из указанной рабочей книги Excel и добавляет её в конец указанной коллекции фигур в заданных координатах.

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для позиционирования диаграммы. |
| y | **float** | Координата Y для позиционирования диаграммы. |
| workbook_path | **str** | Путь к файлу рабочей книги, содержащей диаграмму. |
| worksheet_name | **str** | Имя листа, содержащего диаграмму. |
| chart_name | **str** | Имя диаграммы, которую нужно добавить. |
| embed_workbook | **bool** | Если `true`, рабочая книга будет встроена в диаграмму; <br/><br/>            если `false`, диаграмма будет ссылаться на внешнюю рабочую книгу. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда любой обязательный параметр имеет значение None, пустой, или когда диаграмму невозможно найти в рабочей книге. |
| **RuntimeError(Proxy error(IOException))** | Вызывается, когда при доступе к файлу происходит ошибка ввода/вывода. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Вызывается, когда входные данные имеют неподдерживаемый формат. |



### См. также
* класс [`ExcelWorkbookImporter`](/slides/python-net/ru/aspose.slides.importing/excelworkbookimporter)
* класс [`IExcelDataWorkbook`](/slides/python-net/ru/aspose.slides.excel/iexceldataworkbook)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides.importing`](/slides/python-net/ru/aspose.slides.importing)
* библиотека [`Aspose.Slides`](/slides/python-net)