---
title: "System::Collections::Generic::Details::CastRules"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 365
url: /it/system.collections.generic.details.castrules/
---
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [CastType](./casttype/) | Contiene le funzioni per determinare il tipo di cast. |
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando i tipi di origine e di risultato sono gli stessi. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando il tipo di origine può essere convertito staticamente nel tipo di risultato. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando i tipi non sono gli stessi e il tipo di origine non può essere convertito staticamente nel tipo di risultato. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando il tipo di origine viene incapsulato nella classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando il tipo di origine viene de-incapsulato dalla classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando il tipo di origine viene incapsulato nella classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando il tipo di origine viene de-incapsulato dalla classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Converte il tipo di origine nel tipo di risultato. Usato quando la conversione è invalida o esplicita. |
| **bool** [IsNull](./isnull/)(T) | Verifica che il valore rappresentato sia nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Verifica che il valore rappresentato sia nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Verifica che il valore rappresentato sia nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Verifica la possibilità di cast. |