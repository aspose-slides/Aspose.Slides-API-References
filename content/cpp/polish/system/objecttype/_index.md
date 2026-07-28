---
title: ObjectType
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Udostępnia statyczne metody implementujące pobieranie typu obiektu. Jest to typ statyczny bez usług instancji. Nie należy w żaden sposób tworzyć jego instancji.
type: docs
weight: 1158
url: /pl/system/objecttype/
---
## ObjectType klasa

Provides static methods that implement object type getters. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectType
```

## Metody

| Metoda | Opis |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla inteligentnych wskaźników. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla wyjątków. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementuje tłumaczenie typeof(). Przeciążenie dla typów prymitywnych. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementuje tłumaczenie typeof(). Przeciążenie dla typów [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla typów prymitywnych. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla typów enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla typu string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)