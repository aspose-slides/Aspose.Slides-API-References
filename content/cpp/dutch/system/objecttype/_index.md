---
title: ObjectType
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt statische methoden die objecttype-getters implementeren. Dit is een statisch type zonder instantiediensten. U mag er onder geen enkele omstandigheid instanties van maken.
type: docs
weight: 1158
url: /nl/system/objecttype/
---
## ObjectType klasse

Biedt statische methoden die objecttype-getters implementeren. Dit is een statisch type zonder instantiediensten. U zou er onder geen enkele omstandigheid instanties van moeten maken.

```cpp
class ObjectType
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor slimme pointers. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor structuren. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor uitzonderingen. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementeert typeof()-vertaling. Overload voor primitieve types. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementeert typeof()-vertaling. Overload voor [Nullable](../nullable/)-types. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor primitieve types. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor enum-types. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor structuren en pointers. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor structuren en pointers. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementeert typeof()-vertaling. Overload voor stringtype. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)