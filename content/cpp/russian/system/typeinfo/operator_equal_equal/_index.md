---
title: operator==()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, равны ли текущий объект и указанный объект TypeInfo.
type: docs
weight: 443
url: /ru/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const метод

Определяет, равны ли текущий объект и указанный объект [TypeInfo](../).

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Объект [TypeInfo](../) для сравнения |

### Возвращаемое значение

True если хеши объектов равны, иначе - false

## TypeInfo::operator==(std::nullptr_t) const метод

Определяет, является ли текущий объект [TypeInfo](../) null-объектом, т.е. не представляет никакого типа.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Возвращаемое значение

True если текущий объект [TypeInfo](../) является null-объектом, иначе - false

## См. также

* Класс [TypeInfo](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)