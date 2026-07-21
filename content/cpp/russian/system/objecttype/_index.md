---
title: ObjectType
second_title: Aspose.Slides для C++ справочник API
description: Предоставляет статические методы, реализующие получение типов объектов. Это статический тип без экземплярных сервисов. Вы никогда не должны создавать его экземпляры любыми способами.
type: docs
weight: 1145
url: /ru/system/objecttype/
---
## ObjectType класс

Предоставляет статические методы, реализующие получение типов объектов. Это статический тип без экземплярных сервисов. Вам никогда не следует создавать его экземпляры любыми способами.

```cpp
class ObjectType
```

## Методы

| Метод | Описание |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для умных указателей. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для структур. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для исключений. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Реализует перевод typeof(). Перегрузка для примитивных типов. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Реализует перевод typeof(). Перегрузка для типов [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для примитивных типов. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для enum-типов. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для структур и указателей. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для структур и указателей. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Реализует перевод typeof(). Перегрузка для строкового типа. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)