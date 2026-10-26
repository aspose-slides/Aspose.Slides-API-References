---
title: check_write_protection method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Проверяет, правильно ли указан пароль для изменения защищённой от записи презентации.

### Возвращаемое значение

True если презентация защищена от записи и пароль верен. False в противном случае.



```python
def check_write_protection(self, password):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| password | **str** | Пароль для проверки. |

### Примечания

1. Вы должны проверить свойство [`IPresentationInfo.is_write_protected`](/slides/python-net/ru/aspose.slides/ipresentationinfo/is_write_protected) перед вызовом этого метода.
2. Когда password равно None или пусто, этот метод возвращает false.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### См. также
* класс [`IPresentationInfo`](/slides/python-net/ru/aspose.slides/ipresentationinfo)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)