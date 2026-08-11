---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides برای مرجع API C++
description: آداپتور برای استفاده از IEqualityComparer برای هش‌گذاری. در صورت تنظیم، از شی مقایسه‌کننده استفاده می‌کند؛ در غیر این صورت، از روش هش موجود که با استفاده از ساختار DictionaryHashSelector انتخاب شده است، استفاده می‌کند.
type: docs
weight: 677
url: /fa/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter ساختار

آداپتور برای استفاده از [IEqualityComparer](../iequalitycomparer/) برای هش‌گذاری. در صورت تنظیم، از شی مقایسه‌کننده استفاده می‌کند؛ در غیر این صورت، از روش هش موجود که با استفاده از [DictionaryHashSelector](../dictionaryhashselector/) ساختار انتخاب شده است، استفاده می‌کند.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Hashed | نوع. |

## متدها

| متد | توضیح |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | آداپتور را بدون مقایسه‌کننده‌ای که استفاده شود ایجاد می‌کند. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | آداپتور را با مقایسه‌کننده داده‌شده‌ای که استفاده شود ایجاد می‌کند. |
| std::size_t [operator()](./operator_call/)(const T\&) const | مقدار هش را محاسبه می‌کند. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | مقایسه‌کننده‌ای که استفاده شود را تنظیم می‌کند. |

## موارد مرتبط

* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)