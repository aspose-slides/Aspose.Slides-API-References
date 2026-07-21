---
title: operator!=()
second_title: Aspose.Slides для C++ API Reference
description: Оператор сравнения на неравенство.
type: docs
weight: 313
url: /ru/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const метод

Оператор сравнения на неравенство.

```cpp
bool System::String::operator!=(const String &str) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для сравнения с текущим. |

### Возвращаемое значение

false, если обе строки null или обе не null и совпадают, иначе true.

## String::operator!=(std::nullptr_t) const метод

Проверяет, что строка не null. Применяет ту же логику, что и вызов [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Возвращаемое значение

false, если строка null, иначе true.

## Смотрите также

* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)