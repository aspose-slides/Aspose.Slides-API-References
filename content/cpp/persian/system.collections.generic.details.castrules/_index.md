---
title: "System::Collections::Generic::Details::CastRules"
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 365
url: /fa/system.collections.generic.details.castrules/
---
## ساختارها

| ساختار | توضیحات |
| --- | --- |
| [CastType](./casttype/) | شامل توابعی برای تعیین نوع تبدیل است. |
## توابع

| تابع | توضیحات |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع و نوع نتیجه یکسان باشند، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع بتواند به‌صورت ایستا به نوع نتیجه تبدیل شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع‌ها یکسان نیستند و نوع منبع نتواند به‌صورت ایستا به نوع نتیجه تبدیل شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع به یک شیء کلاس [Nullable](../system/nullable/) بسته می‌شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع از نمونهٔ کلاس [Nullable](../system/nullable/) استخراج می‌شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع به یک شیء کلاس [Object](../system/object/) بسته می‌شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که نوع منبع از نمونهٔ کلاس [Object](../system/object/) استخراج می‌شود، استفاده می‌شود. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | نوع منبع را به نوع نتیجه تبدیل می‌کند. هنگامی که تبدیل نامعتبر باشد یا تبدیل صریح باشد، استفاده می‌شود. |
| **bool** [IsNull](./isnull/)(T) | بررسی می‌کند که مقدار نمایان شده nullptr باشد. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | بررسی می‌کند که مقدار نمایان شده nullptr باشد. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | بررسی می‌کند که مقدار نمایان شده nullptr باشد. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | امکان تبدیل را بررسی می‌کند. |