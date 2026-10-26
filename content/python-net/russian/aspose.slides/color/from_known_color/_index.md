---
title: from_known_color method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Создает цвет из указанного предопределенного цвета.<br/>Это единственный способ получить системный цвет (например `KnownColor.CONTROL`): системные цвета не доступны как атрибуты `Color`, поскольку их значения зависят от темы рабочего стола, поэтому они читаются из среды выполнения библиотеки.

### Возвращаемое значение

Цвет, который создает этот метод.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| known_color | **KnownColor** | Элемент перечисления `KnownColor` (IntEnum, отражающего .NET `System.Drawing.KnownColor`) или его целочисленное значение. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **ValueError** | Значение не является допустимым членом `KnownColor`. |



### См. также
* класс [`Color`](/slides/python-net/ru/aspose.slides/color)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)