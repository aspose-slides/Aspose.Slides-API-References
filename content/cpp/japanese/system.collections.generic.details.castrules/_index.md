---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 365
url: /ja/system.collections.generic.details.castrules/
---
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [CastType](./casttype/) | キャストタイプを決定する関数を含みます。 |
## 関数

| 関数 | 説明 |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型と結果型が同じ場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型を静的にキャストできる場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。型が同じでなく、ソース型を静的にキャストできない場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型が [Nullable](../system/nullable/) クラスのインスタンスにボックス化される場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型が [Nullable](../system/nullable/) クラスのインスタンスからアンボックス化される場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型が [Object](../system/object/) クラスのインスタンスにボックス化される場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。ソース型が [Object](../system/object/) クラスのインスタンスからアンボックス化される場合に使用します。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | ソース型を結果型にキャストします。キャストが無効であるか、変換が明示的な場合に使用します。 |
| **bool** [IsNull](./isnull/)(T) | 表示された値が nullptr であるかチェックします。 |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | 表示された値が nullptr であるかチェックします。 |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | 表示された値が nullptr であるかチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | キャスト可能性をチェックします。 |