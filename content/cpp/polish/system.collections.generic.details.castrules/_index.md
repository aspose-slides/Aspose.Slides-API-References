---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: 
type: docs
weight: 365
url: /pl/system.collections.generic.details.castrules/
---
## Struktury

| Struktura | Opis |
| --- | --- |
| [CastType](./casttype/) | Zawiera funkcje określające typ rzutowania. |
## Funkcje

| Funkcja | Opis |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typy źródłowy i wynikowy są takie same. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy może być statycznie rzutowany na typ wynikowy. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typy nie są takie same i typ źródłowy nie może być statycznie rzutowany na typ wynikowy. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest pakowany do instancji klasy [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest rozpakowywany z instancji klasy [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest pakowany do instancji klasy [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy typ źródłowy jest rozpakowywany z instancji klasy [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Rzutuje typ źródłowy na typ wynikowy. Używane, gdy rzutowanie jest nieprawidłowe lub konwersja jest explicite. |
| **bool** [IsNull](./isnull/)(T) | Sprawdza, czy reprezentowana wartość jest nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Sprawdza, czy reprezentowana wartość jest nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Sprawdza, czy reprezentowana wartość jest nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Sprawdza możliwość rzutowania. |