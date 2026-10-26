---
title: "System::Collections::Generic::Details::CastRules"
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 365
url: /fr/system.collections.generic.details.castrules/
---
## Structures

| Structure | Description |
| --- | --- |
| [CastType](./casttype/) | Contient les fonctions permettant de déterminer le type de conversion. |
## Fonctions

| Fonction | Description |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source et le type résultat sont identiques. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source peut être converti statiquement en type résultat. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque les types ne sont pas identiques et que le type source ne peut pas être converti statiquement en type résultat. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source est encapsulé dans une instance de la classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source est désencapsulé d’une instance de la classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source est encapsulé dans une instance de la classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque le type source est désencapsulé d’une instance de la classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Convertit le type source en type résultat. Utilisé lorsque la conversion est invalide ou que la conversion est explicite. |
| **bool** [IsNull](./isnull/)(T) | Vérifie que la valeur représentée est nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Vérifie que la valeur représentée est nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Vérifie que la valeur représentée est nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Vérifie la possibilité de conversion. |