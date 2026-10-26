---
title: check_password method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Проверяет, является ли пароль корректным для презентации, защищённой открытым паролем.

### Возвращаемое значение

True, если презентация защищена открытым паролем и пароль корректен, иначе false.



```python
def check_password(self, password):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| password | **str** | Пароль для проверки. |

### Замечания

Если пароль равен None или пустой, этот метод возвращает false.

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Смотрите также
* класс [`PresentationInfo`](/slides/python-net/ru/aspose.slides/presentationinfo)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)