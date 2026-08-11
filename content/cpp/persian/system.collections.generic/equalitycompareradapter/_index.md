---
title: EqualityComparerAdapter
second_title: Aspose.Slides برای مرجع API C++
description: "آداپتری که امکان استفاده از IEqualityComparer را با مجموعه‌ها و الگوریتم‌های سبک STL فراهم می‌کند. اگر تنظیم شده باشد از IEqualityComparer استفاده می‌کند. در صورت عدم تنظیم، از عملگر ==، Object::Equals یا T::Equals استفاده می‌کند، هر کدام که در دسترس باشد."
type: docs
weight: 664
url: /fa/system.collections.generic/equalitycompareradapter/
---
## ساختار EqualityComparerAdapter

آداپتری که امکان استفاده از [IEqualityComparer](../iequalitycomparer/) را با مجموعه‌ها و الگوریتم‌های سبک STL فراهم می‌کند. از [IEqualityComparer](../iequalitycomparer/) استفاده می‌کند، اگر تنظیم شده باشد. در صورت عدم تنظیم، از عملگر ==، [Object::Equals](../../system/object/equals/) یا T::Equals استفاده می‌کند، بسته به اینکه کدام یک در دسترس باشد.

```cpp
template<class T>class EqualityComparerAdapter
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که مقایسه می‌شود. |

## متدها

| متد | توضیح |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | آداپتری را ایجاد می‌کند که از هیچ مقایسه‌کننده‌ای استفاده نمی‌کند. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | آداپتری را با مقایسه‌کنندهٔ داده‌شده ایجاد می‌کند. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | دو شیء را مقایسه می‌کند. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | مقایسه‌کننده را تنظیم می‌کند. |

## موارد مرتبط

* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)