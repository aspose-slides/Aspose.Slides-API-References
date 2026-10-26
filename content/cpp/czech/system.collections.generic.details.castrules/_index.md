---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 365
url: /cs/system.collections.generic.details.castrules/
---
## Struktury

| Struktura | Popis |
| --- | --- |
| [CastType](./casttype/) | Obsahuje funkce pro určení typu převodu. |
## Funkce

| Funkce | Popis |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když jsou typy zdroje a výsledku stejné. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když lze typ zdroje staticky převést na typ výsledku. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když typy nejsou stejné a typ zdroje nelze staticky převést na typ výsledku. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když je typ zdroje zabalen do instance třídy [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když je typ zdroje rozbalen z instance třídy [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když je typ zdroje zabalen do instance třídy [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když je typ zdroje rozbalen z instance třídy [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Převádí typ zdroje na typ výsledku. Používá se, když je převod neplatný nebo je konverze explicitní. |
| **bool** [IsNull](./isnull/)(T) | Kontroluje, že reprezentovaná hodnota je nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Kontroluje, že reprezentovaná hodnota je nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Kontroluje, že reprezentovaná hodnota je nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Kontroluje možnost převodu. |