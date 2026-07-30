---
title: ObjectType
second_title: Aspose.Slides pro C++ API referenci
description: Poskytuje statické metody, které implementují získávače typů objektů. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance žádným způsobem.
type: docs
weight: 1158
url: /cs/system/objecttype/
---
## ObjectType třída

Poskytuje statické metody, které implementují získávače typů objektů. Jedná se o statický typ bez instančních služeb. Měli byste nikdy nevytvářet jeho instance žádným způsobem.

```cpp
class ObjectType
```

## Metody

| Metoda | Popis |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro chytré ukazatele. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro struktury. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro výjimky. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementuje překlad typeof(). Přetížení pro primitivní typy. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementuje překlad typeof(). Přetížení pro typy [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro primitivní typy. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro enum typy. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro struktury a ukazatele. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro struktury a ukazatele. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementuje překlad typeof(). Přetížení pro typ stringu. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)