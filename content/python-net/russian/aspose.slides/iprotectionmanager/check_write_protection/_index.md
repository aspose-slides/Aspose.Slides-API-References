---
title: check_write_protection method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Определяет, защищена ли презентация паролем от изменения.

### Returns
True, если пароль действителен; иначе false.

```python
def check_write_protection(self, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| password | **str** | Пароль для проверки. |

### Remarks
1. Перед вызовом этого метода следует проверить свойство [`IProtectionManager.is_write_protected`](/slides/python-net/ru/aspose.slides/iprotectionmanager/is_write_protected).
2. Если пароль равен None или пустой, этот метод возвращает false.

### See Also
* класс [`IProtectionManager`](/slides/python-net/ru/aspose.slides/iprotectionmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)