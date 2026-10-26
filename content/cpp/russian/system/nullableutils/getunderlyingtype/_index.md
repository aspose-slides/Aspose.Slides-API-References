---
title: GetUnderlyingType()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает базовый тип аргумента указанного nullable типа.
type: docs
weight: 1
url: /ru/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) метод

Возвращает базовый тип аргумента указанного nullable типа.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | Объект System.Type, описывающий закрытый обобщённый nullable тип. |

### Возвращаемое значение

Типовой аргумент параметра nullableType, если параметр nullableType является закрытым обобщённым nullable типом; иначе null

## См. также

* Класс [TypeInfo](../../typeinfo/)
* Класс [NullableUtils](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)