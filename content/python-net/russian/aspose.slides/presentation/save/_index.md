---
title: save method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML.


```python
def save(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ru/aspose.slides.export.xaml/ixamloptions) | Параметры формата XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Сохраняет все слайды презентации в файл с указанным форматом.


```python
def save(self, fname, format):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| fname | **str** | Путь к создаваемому файлу. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Сохраняет все слайды презентации в поток в указанном формате.


```python
def save(self, stream, format):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Выходной поток. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}


```python
def save(self, fname, format, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами.


```python
def save(self, stream, format, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Выходной поток. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) | Дополнительные параметры формата. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Если попытаться сохранить зашифрованный файл в <br/>            формат, не поддерживаемый Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Сохраняет указанные слайды презентации в файл с указанным форматом, сохраняя номера страниц.


```python
def save(self, fname, slides, format):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| fname | **str** | Путь к создаваемому файлу. |
| slides | **List[int]** | Массив с позициями слайдов, начиная с 1. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Когда параметр stream или slides имеет значение None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Когда параметр slides содержит неправильные номера страниц. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Когда используется неподдерживаемый SaveFormat, например PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Сохраняет указанные слайды презентации в поток в указанном формате, сохраняя номера страниц.


```python
def save(self, stream, slides, format):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Выходной поток. |
| slides | **List[int]** | Массив с позициями слайдов, начиная с 1. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Сохраняет указанные слайды презентации в файл с указанным форматом, сохраняя номера страниц.


```python
def save(self, fname, slides, format, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| fname | **str** | Путь к создаваемому файлу. |
| slides | **List[int]** | Массив с позициями слайдов, начиная с 1. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) | Дополнительные параметры формата. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Сохраняет указанные слайды презентации в поток в указанном формате, сохраняя номера страниц.


```python
def save(self, stream, slides, format, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Выходной поток. |
| slides | **List[int]** | Массив с позициями слайдов, начиная с 1. |
| format | [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat) | Формат экспортируемых данных. |
| options | [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions) | Дополнительные параметры формата. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Когда параметр stream или slides имеет значение None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Когда параметр slides содержит неправильные номера страниц. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Когда используется неподдерживаемый SaveFormat, например PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### См. также
* класс [`ISaveOptions`](/slides/python-net/ru/aspose.slides.export/isaveoptions)
* класс [`IXamlOptions`](/slides/python-net/ru/aspose.slides.export.xaml/ixamloptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* перечисление [`SaveFormat`](/slides/python-net/ru/aspose.slides.export/saveformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)