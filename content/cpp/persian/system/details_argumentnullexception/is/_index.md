---
title: Is()
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 27
url: /fa/system/details_argumentnullexception/is/
---
## جزئیات_ArgumentNullException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_ArgumentNullException::Is(const System::TypeInfo &target) const override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) ساختاری که نوعی را برای تست شیء جاری در مقابل آن توصیف می‌کند. |

### مقدار بازگشتی

در صورتی که شیء از نوع برچسب‌خورده یا زیرکلاس آن باشد، true؛ در غیر این صورت false.

## ملاحظات

بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#.

## ارجاع‌ها

* کلاس [TypeInfo](../../typeinfo/)
* کلاس [Details_ArgumentNullException](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)