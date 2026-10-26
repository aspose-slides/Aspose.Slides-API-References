---
title: add method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Добавляет новый пользовательский xml-фрагмент.

### Возвращаемое значение

Создана часть пользовательского xml-фрагмента.



```python
def add(self, xml_string):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| xml_string | **str** | Строка xml новой части, которую следует добавить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString пуст или xml-данные недействительны. |


## add(self, xml_data) {#bytes}
Добавляет новый пользовательский xml-фрагмент.

### Возвращаемое значение

Создана часть пользовательского xml-фрагмента.



```python
def add(self, xml_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| xml_data | **bytes** | Данные xml новой части, которую следует добавить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData пуст или недействителен. |


## add(self, input_stream) {#iorawiobase}
Добавляет новый пользовательский xml-фрагмент.

### Возвращаемое значение

Создана часть пользовательского xml-фрагмента.



```python
def add(self, input_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Поток ввода с данными xml новой части, которую следует добавить. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Данные в inputStream пусты или недействительны. |



### См. также
* класс [`CustomXmlPartCollection`](/slides/python-net/ru/aspose.slides/customxmlpartcollection)
* класс [`ICustomXmlPart`](/slides/python-net/ru/aspose.slides/icustomxmlpart)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)