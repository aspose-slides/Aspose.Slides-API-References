---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 365
url: /sv/system.collections.generic.details.castrules/
---
## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [CastType](./casttype/) | Innehåller funktionerna för att bestämma omvandlingstypen. |
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när käll- och resulttypen är samma. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när källtypen kan statiskt omvandlas till resulttypen. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när typerna inte är samma och källtypen inte kan statiskt omvandlas till resulttypen. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när källtypen blir boxad till [Nullable](../system/nullable/) klassinstans. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när källtypen blir unboxad från [Nullable](../system/nullable/) klassinstans. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när källtypen blir boxad till [Object](../system/object/) klassinstans. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när källtypen blir unboxad från [Object](../system/object/) klassinstans. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Omvandlar källtypen till resulttypen. Används när omvandlingen är ogiltig eller konverteringen är explicit. |
| **bool** [IsNull](./isnull/)(T) | Kontrollerar att det representerade värdet är nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Kontrollerar att det representerade värdet är nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Kontrollerar att det representerade värdet är nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Kontrollerar omvandlingsmöjligheten. |