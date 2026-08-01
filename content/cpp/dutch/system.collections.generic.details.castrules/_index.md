---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 365
url: /nl/system.collections.generic.details.castrules/
---
## Structuren

| Structuur | Beschrijving |
| --- | --- |
| [CastType](./casttype/) | Bevat de functies om het casttype te bepalen. |

## Functies

| Functie | Beschrijving |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het bron- en het resulttype gelijk zijn. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het brontype statisch kan worden gecast naar het resulttype. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer de types niet gelijk zijn en het brontype niet statisch kan worden gecast naar het resulttype. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het brontype wordt geboxed naar de [Nullable](../system/nullable/) class-instantie. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het brontype wordt uitgeboxt uit de [Nullable](../system/nullable/) class-instantie. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het brontype wordt geboxed naar de [Object](../system/object/) class-instantie. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer het brontype wordt uitgeboxt uit de [Object](../system/object/) class-instantie. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Cast het brontype naar het resulttype. Wordt gebruikt wanneer de cast ongeldig is of de conversie expliciet is. |
| **bool** [IsNull](./isnull/)(T) | Controleert of de weergegeven waarde nullptr is. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Controleert of de weergegeven waarde nullptr is. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Controleert of de weergegeven waarde nullptr is. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Controleert de castmogelijkheid. |