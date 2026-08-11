---
title: Interlocked
second_title: مرجع API Aspose.Slides برای C++
description: API ای برای عملیات ایمن در برابر رشته‌ها فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه از آن نمونه‌ای ایجاد کنید.
type: docs
weight: 131
url: /fa/system.threading/interlocked/
---
## Interlocked کلاس

API ای برای عملیات ایمن در برابر رشته‌ها فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه از آن نمونه‌ای ایجاد کنید.

```cpp
class Interlocked
```

## متدها

| متد | توضیح |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | مقدار را به صورت اتمی افزایش می‌دهد. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | مقدار را به صورت اتمی افزایش می‌دهد. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | مقدار متغیر را مقایسه‌و-تبادله می‌کند: بررسی می‌کند که آیا متغیر با مقدار خاصی برابر است و فقط در صورت مطابقت مقدار ذخیره‌شده با مقدار مورد انتظار، مقدار جدید را ذخیره می‌کند. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | مقدار متغیر را مقایسه‌و-تبادله می‌کند: بررسی می‌کند که آیا متغیر با مقدار خاصی برابر است و فقط در صورت مطابقت مقدار ذخیره‌شده با مقدار مورد انتظار، مقدار جدید را ذخیره می‌کند. پیاده‌سازی نشده است. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | مقدار متغیر را مقایسه‌و-تبادله می‌کند: بررسی می‌کند که آیا متغیر با مقدار خاصی برابر است و فقط در صورت مطابقت مقدار ذخیره‌شده با مقدار مورد انتظار، مقدار جدید را ذخیره می‌کند. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | مقدار را به صورت اتمی کاهش می‌دهد. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | مقدار را به صورت اتمی کاهش می‌دهد. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | مقدار متغیر را تعویض می‌کند: مقدار جدید را ذخیره می‌کند و مقدار متغیر را پیش از ذخیره‌سازی برمی‌گرداند. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | مقدار متغیر را تعویض می‌کند: مقدار جدید را ذخیره می‌کند و مقدار متغیر را پیش از ذخیره‌سازی برمی‌گرداند. پیاده‌سازی نشده است. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | مقدار را به صورت اتمی از طریق روش exchange-add افزایش می‌دهد. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | مقدار را به صورت اتمی از طریق روش exchange-add افزایش می‌دهد. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | مقدار را به صورت اتمی افزایش می‌دهد. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | مقدار را به صورت اتمی افزایش می‌دهد. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | یک مقدار 64-بیتی را برمی‌گرداند که به عنوان عملیات اتمی بارگذاری شده است. |

## همچنین ببینید

* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)