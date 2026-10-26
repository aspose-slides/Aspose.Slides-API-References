---
title: add method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Добавляет новый пользовательский xml-раздел.

### Возвращаемое значение

Создан пользовательский xml-раздел.



```python
def add(self, xml_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| xml_data | **bytes** | XML-данные нового раздела, который будет добавлен. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData пустой или недействительный. |


## add(self, xml_string) {#str}
Добавляет новый пользовательский xml-раздел.

### Возвращаемое значение

Создан пользовательский xml-раздел.



```python
def add(self, xml_string):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| xml_string | **str** | XML-строка нового раздела, который будет добавлен. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString пустой или xml-данные недействительны. |


## add(self, input_stream) {#iorawiobase}
Добавляет новый пользовательский xml-раздел.

### Возвращаемое значение

Создан пользовательский xml-раздел.



```python
def add(self, input_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Поток inputStream с XML-данными нового раздела, который будет добавлен. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream имеет значение `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Данные в inputStream пусты или Sinvalid. |



### См. также
* класс [`ICustomXmlPart`](/slides/python-net/ru/aspose.slides/icustomxmlpart)
* класс [`ICustomXmlPartCollection`](/slides/python-net/ru/aspose.slides/icustomxmlpartcollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)