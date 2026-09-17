---
title: Presentation constructor
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Этот конструктор создаёт новую презентацию с нуля.
            Созданная презентация имеет один пустой слайд.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Этот конструктор создаёт новую презентацию с нуля.
            Созданная презентация имеет один пустой слайд.


```python
def __init__(self, load_options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions) | Дополнительные параметры загрузки. |


## __init__(self, stream) {#iorawiobase}
Этот конструктор является основным механизмом чтения существующей презентации.


```python
def __init__(self, stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Входной поток. |


## __init__(self, file) {#str}
Этот конструктор получает путь к исходному файлу, из которого
             читается содержимое презентации.


```python
def __init__(self, file):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| file | **str** | Входной файл. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда входной файл имеет нулевую длину |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Этот конструктор является основным механизмом чтения существующей презентации.


```python
def __init__(self, stream, load_options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Входной поток. |
| load_options | [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions) | Дополнительные параметры загрузки. |


## __init__(self, file, load_options) {#str-loadoptions}
Этот конструктор получает путь к исходному файлу, из которого
            читается содержимое презентации.


```python
def __init__(self, file, load_options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| file | **str** | Входной файл. |
| load_options | [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions) | Дополнительные параметры загрузки. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда входной файл имеет нулевую длину |



### См. также
* класс [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)