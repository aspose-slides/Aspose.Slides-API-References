---
title: "System::Collections::Generic::Details::CastRules"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 365
url: /ru/system.collections.generic.details.castrules/
---
## Структуры

| Структура | Описание |
| --- | --- |
| [CastType](./casttype/) | Содержит функции для определения типа приведения. |
## Функции

| Функция | Описание |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда типы источника и результата одинаковы. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда тип источника может быть статически преобразован в тип результата. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда типы различаются и тип источника нельзя статически преобразовать в тип результата. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда тип источника упаковывается в экземпляр класса [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда тип источника распаковывается из экземпляра класса [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда тип источника упаковывается в экземпляр класса [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда тип источника распаковывается из экземпляра класса [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Преобразует тип источника в тип результата. Используется, когда приведение недопустимо или преобразование является явным. |
| **bool** [IsNull](./isnull/)(T) | Проверяет, что представленное значение является nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Проверяет, что представленное значение является nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Проверяет, что представленное значение является nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Проверяет возможность приведения. |