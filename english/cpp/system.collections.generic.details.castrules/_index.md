---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 365
url: /cpp/system.collections.generic.details.castrules/
---



## Structures

| Struct | Description |
| --- | --- |
| [CastType](./casttype/) | Contains the functions to determine the cast type. |
## Functions

| Function | Description |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source and the result types are the same. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source type can be statically cast to the result type. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the types aren't the same and the source type cannot be statically cast to the result type. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source type is being boxed to the [Nullable](../system/nullable/) class instance. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source type is being unboxed from the [Nullable](../system/nullable/) class instance. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source type is being boxed to the [Object](../system/object/) class instance. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the source type is being unboxed from the [Object](../system/object/) class instance. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Casts the source type to the result type. Used when the casting is invalid or the conversion is explicit. |
| **bool** [IsNull](./isnull/)(T) | Checks that the represented value is nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Checks that the represented value is nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Checks that the represented value is nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Checks the cast possibility. |
