---
title: ExceptionWrapper
second_title: Aspose.Slides برای C++ مرجع API
description: قالبی که نمایانگر wrapper از استثناهایی است که از کلاس Exception مشتق شده‌اند.
type: docs
weight: 833
url: /fa/system/exceptionwrapper/
---
## کلاس ExceptionWrapper

قالبی که نمایانگر wrapper از استثناهایی است که از کلاس Exception مشتق شده‌اند.

```cpp
template<typename T>class ExceptionWrapper
```

## متدها

| متد | توضیح |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | یک نمونه null-instance از کلاس [ExceptionWrapper](./) را می‌سازد که هیچ استثنایی را نشان نمی‌دهد. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | یک نمونه از کلاس [ExceptionWrapper](./) را می‌سازد که اشاره‌گر عبور داده‌شده را شامل می‌شود. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | سازندهٔ کپی. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | سازندهٔ انتقال. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | سازنده‌ای که پارامترها را به سازنده‌های کلاس Exception منتقل می‌کند و یک smart pointer ایجاد می‌سازد که نمونهٔ جدید کلاس Exception را نگه می‌دارد. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | عملگر تبدیل ضمنی به SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | اجازه دسترسی به اعضای شیء Exception را می‌دهد. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | عملگر تخصیص. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | عملگر تخصیص انتقالی. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../typeinfo/) برای نوع Exception. |

## تعاریف نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [ExceptionType](./exceptiontype/) | برای توابع تبدیل استفاده می‌شود. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)