---
title: operator==()
second_title: Aspose.Slides для C++ Справочник API
description: Оператор сравнения на равенство.
type: docs
weight: 300
url: /ru/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const метод


Оператор сравнения на равенство.

```cpp
bool System::String::operator==(const String &str) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для сравнения с текущей. |

### Возвращаемое значение

true если обе строки null или обе не null и совпадают, false в противном случае.

## String::operator==(std::nullptr_t) const метод


Проверяет, является ли строка null. Применяет ту же логику, что и вызов [IsNull()](../isnull/).

```cpp
bool System::String::operator==(std::nullptr_t) const
```


### Возвращаемое значение

true если строка null, false в противном случае.

## См. также

* Класс [String](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)