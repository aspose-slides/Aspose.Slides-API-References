---
title: ObjectType
second_title: Aspose.Slides for C++ API Referenciája
description: Statikus metódusokat biztosít, amelyek megvalósítják az objektumtípus lekérőket. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni belőle semmilyen módon.
type: docs
weight: 1158
url: /hu/system/objecttype/
---
## ObjectType osztály

Statikus metódusokat biztosít, amelyek megvalósítják az objektumtípus lekérőket. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni belőle semmilyen módon.

```cpp
class ObjectType
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementálja a typeof() fordítást. Túlterhelés okos mutatókhoz. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementálja a typeof() fordítást. Túlterhelés struktúrákhoz. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementálja a typeof() fordítást. Túlterhelés kivételekhez. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementálja a typeof() fordítást. Túlterhelés primitív típusokhoz. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementálja a typeof() fordítást. Túlterhelés a [Nullable](../nullable/) típusokhoz. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés primitív típusokhoz. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés enum típusokhoz. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés struktúrák és mutatók számára. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a [Nullable](../nullable/) számára. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a MutlicastDelegate számára. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés struktúrák és mutatók számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementálja a typeof() fordítást. Túlterhelés string típusra. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementálja a typeof() fordítást. Túlterhelés a **uint8_t** számára. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)