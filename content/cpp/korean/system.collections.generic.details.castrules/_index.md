---
title: "System::Collections::Generic::Details::CastRules"
second_title: "Aspose.Slides for C++ API 참조"
description: 
type: docs
weight: 365
url: /ko/system.collections.generic.details.castrules/
---
## 구조체

| Struct | Description |
| --- | --- |
| [CastType](./casttype/) | 캐스트 타입을 결정하는 함수들을 포함합니다. |
## 함수

| Function | Description |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스와 결과 타입이 동일할 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스 타입을 정적으로 결과 타입으로 변환할 수 있을 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 타입이 동일하지 않고 소스 타입을 정적으로 결과 타입으로 변환할 수 없을 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스 타입이 [Nullable](../system/nullable/) 클래스 인스턴스로 박싱될 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스 타입이 [Nullable](../system/nullable/) 클래스 인스턴스에서 언박싱될 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스 타입이 [Object](../system/object/) 클래스 인스턴스로 박싱될 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 소스 타입이 [Object](../system/object/) 클래스 인스턴스에서 언박싱될 때 사용됩니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | 소스 타입을 결과 타입으로 변환합니다. 캐스팅이 잘못되었거나 변환이 명시적인 경우에 사용됩니다. |
| **bool** [IsNull](./isnull/)(T) | 표현된 값이 nullptr인지 확인합니다. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | 표현된 값이 nullptr인지 확인합니다. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | 표현된 값이 nullptr인지 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | 캐스트 가능성을 확인합니다. |