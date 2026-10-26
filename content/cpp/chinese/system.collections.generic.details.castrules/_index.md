---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 365
url: /zh/system.collections.generic.details.castrules/
---
## 结构体

| 结构体 | 描述 |
| --- | --- |
| [CastType](./casttype/) | 包含用于确定转换类型的函数。 |
## 函数

| 函数 | 描述 |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型和结果类型相同时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型可以静态转换为结果类型时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当类型不同且源类型无法静态转换为结果类型时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型正被装箱为 [Nullable](../system/nullable/) 类实例时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型正从 [Nullable](../system/nullable/) 类实例中解箱时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型正被装箱为 [Object](../system/object/) 类实例时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当源类型正从 [Object](../system/object/) 类实例中解箱时使用。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | 将源类型转换为结果类型。当转换无效或转换需要显式进行时使用。 |
| **bool** [IsNull](./isnull/)(T) | 检查表示的值是否为 nullptr。 |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | 检查表示的值是否为 nullptr。 |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | 检查表示的值是否为 nullptr。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | 检查转换的可能性。 |