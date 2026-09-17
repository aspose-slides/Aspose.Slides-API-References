---
title: check_write_protection method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Определяет, защищена ли презентация паролем от изменения.

### Возвращаемое значение

True, если пароль действителен; иначе — false.



```python
def check_write_protection(self, password):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| password | **str** | Пароль для проверки. |

### Примечания

1. Перед вызовом этого метода следует проверить свойство [`ProtectionManager.is_write_protected`](/slides/python-net/ru/aspose.slides/protectionmanager/is_write_protected).
2. Когда пароль равен None или пустой, этот метод возвращает false.



### Смотрите также
* класс [`ProtectionManager`](/slides/python-net/ru/aspose.slides/protectionmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)