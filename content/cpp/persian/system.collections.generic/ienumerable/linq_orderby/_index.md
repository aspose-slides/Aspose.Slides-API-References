---
title: LINQ_OrderBy()
second_title: Aspose.Slides برای C++ مرجع API
description: عناصر یک دنباله را بر حسب مقادیر کلیدی که توسط keySelector انتخاب شده‌اند به ترتیب صعودی مرتب می‌کند.
type: docs
weight: 209
url: /fa/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) متد

عناصر یک دنباله را بر اساس مقادیر کلیدی که توسط keySelector انتخاب شده‌اند به ترتیب صعودی مرتب می‌کند.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Template parameters

| پارامتر | توضیح |
| --- | --- |
| keySelector | تابعی برای استخراج یک کلید از یک عنصر. |

### مقدار بازگشت

یک IOrderedEnumerable که عناصر آن بر حسب یک کلید مرتب شده‌اند

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) متد




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* کلاس [Func](../../../system/func/)
* کلاس [IEnumerable](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)