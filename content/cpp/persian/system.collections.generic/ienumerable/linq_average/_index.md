---
title: LINQ_Average()
second_title: مرجع API Aspose.Slides برای C++
description: میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند.
type: docs
weight: 365
url: /fa/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() متد

میانگین یک دنباله از مقادیر عددی را محاسبه می‌کند.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### مقدار بازگشتی

میانگین مقادیر موجود در دنباله.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) متد

میانگین یک دنباله از مقادیر را که با فراخوانی تابع تبدیل بر هر عنصر از دنباله ورودی به دست می‌آیند، محاسبه می‌کند.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقداری که توسط selector برگردانده می‌شود. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | تابعی برای تبدیل که بر هر عنصر اعمال می‌شود. |

### مقدار بازگشتی

میانگین مقادیر پیش‌بینی‌شده.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) متد

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## موارد مرتبط

* کلاس [IEnumerable](../)
* کلاس [Func](../../../system/func/)
* فضای نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)