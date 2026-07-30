---
title: ObjectType
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi statici che implementano i getter del tipo di oggetto. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 1158
url: /it/system/objecttype/
---
## ObjectType classe

Fornisce metodi statici che implementano i getter del tipo di oggetto. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class ObjectType
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per puntatori intelligenti. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per strutture. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per eccezioni. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementa la traduzione di typeof(). Sovraccarico per tipi [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per tipi enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementa la traduzione di typeof(). Sovraccarico per tipo stringa. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)