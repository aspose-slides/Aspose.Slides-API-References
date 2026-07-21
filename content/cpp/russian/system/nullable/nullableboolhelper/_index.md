---
title: NullableBoolHelper()
second_title: Aspose.Slides для C++ – справочник API
description: Вспомогательная функция для проверки, что this и other оба не null, и вызова lambda в этом случае. Используется в реализации.
type: docs
weight: 105
url: /ru/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const метод

Вспомогательная функция для проверки, что this и **other** оба не null, и вызова lambda в этом случае. Используется в реализации.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Другой nullable тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | Другое nullable значение для сравнения. |
| f | const std::function\<**bool**()>\& | Lambda, вызываемая, если **this** и **other** оба не null. |
| default_if_both_are_null | **bool** | Возвращаемое значение, если оба значения null. |

### Возвращаемое значение

false, если **this** или **other** равно null; **default_if_both_are_null**, если оба null; результат вызова **f**, если оба не null.

## См. также

* Класс [Nullable](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)