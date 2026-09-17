---
title: process method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_file_names | **List[str]** | Массив имён входных файлов презентаций. |
| output_file_name | **str** | Имя выходного файла результирующей объединённой презентации. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда имена входных файлов недействительны или форматы не совпадают. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_file_names | **List[str]** | Массив имён входных файлов презентаций. |
| output_stream | **io.RawIOBase** | Выходной поток. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда имена входных файлов недействительны или форматы не совпадают. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_file_names | **List[str]** | Массив имён входных файлов презентаций. |
| output_file_name | **str** | Имя выходного файла результирующей объединённой презентации. |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) | Дополнительные параметры, определяющие способ сохранения объединённой презентации. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда имена входных файлов недействительны или форматы не совпадают. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Объединяет несколько презентаций PowerPoint одинакового формата в один файл презентации.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_file_names | **List[str]** | Массив имён входных файлов презентаций. |
| output_stream | **io.RawIOBase** | Выходной поток. |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) | Дополнительные параметры, определяющие способ сохранения объединённой презентации. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Вызывается, когда имена входных файлов недействительны или форматы не совпадают. |



### См. также
* класс [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions)
* класс [`Merger`](/slides/python-net/ru/aspose.slides.lowcode/merger)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)