---
title: ObjectType
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller statiska metoder som implementerar objekt typ-hämtare. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1158
url: /sv/system/objecttype/
---
## ObjectType klass

Tillhandahåller statiska metoder som implementerar objekt typ-hämtare. Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class ObjectType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för smarta pekare. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för strukturer. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för undantag. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementerar typeof()-översättning. Överlagring för primitiva typer. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementerar typeof()-översättning. Överlagring för [Nullable](../nullable/) typer. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för primitiva typer. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för enum-typer. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för strukturer och pekare. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för strukturer och pekare. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementerar typeof()-översättning. Överlagring för string-typ. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)