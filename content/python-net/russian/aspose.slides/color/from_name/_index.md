---
title: from_name method
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Создаёт цвет из указанного имени предопределённого цвета.<br/>Поиск не учитывает регистр и игнорирует подчёркивания и пробелы: `"LightBlue"`, `"lightblue"` и `"light_blue"` все преобразуются в `Color.light_blue`. Смотрите страницу класса [`Color`](/slides/python-net/ru/aspose.slides/color) для списка предопределённых цветов.

### Возвращаемое значение

Именованный цвет.



```python
@staticmethod
def from_name(name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| name | **str** | Строка, являющаяся именем предопределённого цвета. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **ValueError** | Указанное имя не является именем предопределённого цвета. |
| **TypeError** | Указанное имя не является строкой. |



### См. также
* класс [`Color`](/slides/python-net/ru/aspose.slides/color)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)