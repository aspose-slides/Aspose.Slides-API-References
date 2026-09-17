---
title: check_write_protection method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Проверяет, является ли пароль для изменения корректным для презентации, защищённой от записи.

### Returns

True, если презентация защищена от записи и пароль корректен. False в противном случае.



```python
def check_write_protection(self, password):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| password | **str** | Пароль для проверки. |

### Remarks

1. Следует проверить свойство [`PresentationInfo.is_write_protected`](/slides/python-net/ru/aspose.slides/presentationinfo/is_write_protected) перед вызовом этого метода.
2. Когда пароль равен None или пуст, этот метод возвращает false.

### Exceptions

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### See Also
* класс [`PresentationInfo`](/slides/python-net/ru/aspose.slides/presentationinfo)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)