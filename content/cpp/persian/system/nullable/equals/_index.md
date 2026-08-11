---
title: Equals()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند آیا مقدار نمایش داده شده توسط شیء فعلی برابر با مقدار نمایش داده شده توسط شیء Nullable مشخص شده است.
type: docs
weight: 131
url: /fa/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const متد

تعیین می‌کند آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص‌شده است.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع پایهٔ شیء [Nullable](../) برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک ارجاع ثابت به شیء [Nullable](../) برای مقایسه |

### مقدار بازگشت

در صورتی که مقدار نمایان‌شده توسط شیء جاری برابر با مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص‌شده باشد، true؛ در غیر این صورت false

## موارد مرتبط

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)