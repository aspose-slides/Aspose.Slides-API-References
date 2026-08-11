---
title: ExceptionWrapper()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمونه‌ی null از کلاس ExceptionWrapper ایجاد می‌کند که هیچ استثنایی را نشان نمی‌دهد.
type: docs
weight: 14
url: /fa/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) سازنده

یک نمونه‌ی null از کلاس [ExceptionWrapper](../) ایجاد می‌کند که هیچ استثنایی را نشان نمی‌دهد.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) سازنده

یک نمونه از کلاس [ExceptionWrapper](../) ایجاد می‌کند که اشاره‌گر عبور داده‌شده را شامل می‌شود.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | اشاره‌گر هوشمند به نمونه‌ی کلاس Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) سازنده

سازندهٔ کپی.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | نمونه دیگر از کلاس wrapper که باید کپی شود. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) سازنده

سازندهٔ انتقال.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | نمونه دیگر از کلاس wrapper که باید منتقل شود. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) سازنده

سازنده‌ای که پارامترها را به سازندگان کلاس Exception ارجاع می‌دهد و اشاره‌گر هوشمندی ایجاد می‌کند که نمونه‌ی جدید کلاس Exception را نگه می‌دارد.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## موارد مرتبط

* تعریف‌نوع [ExceptionPtr](../../exceptionptr/)
* کلاس [ExceptionWrapper](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)