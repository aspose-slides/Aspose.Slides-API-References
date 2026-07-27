---
title: "System::Collections::Generic::Details::CastRules"
second_title: "Referencia de la API de Aspose.Slides para C++"
description: 
type: docs
weight: 365
url: /es/system.collections.generic.details.castrules/
---
## Estructuras

| Estructura | Descripción |
| --- | --- |
| [CastType](./casttype/) | Contiene las funciones para determinar el tipo de conversión. |
## Funciones

| Función | Descripción |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando los tipos de origen y de resultado son los mismos. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen puede convertirse estáticamente al tipo de resultado. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando los tipos no son iguales y el tipo de origen no puede convertirse estáticamente al tipo de resultado. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está encapsulando en la instancia de la clase [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está desencapsulando de la instancia de la clase [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está encapsulando en la instancia de la clase [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está desencapsulando de la instancia de la clase [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Convierte el tipo de origen al tipo de resultado. Se usa cuando la conversión es inválida o la conversión es explícita. |
| **bool** [IsNull](./isnull/)(T) | Comprueba que el valor representado es nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Comprueba que el valor representado es nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Comprueba que el valor representado es nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Comprueba la posibilidad de conversión. |