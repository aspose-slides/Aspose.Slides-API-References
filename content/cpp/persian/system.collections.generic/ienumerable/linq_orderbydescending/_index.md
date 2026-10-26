---
title: LINQ_OrderByDescending()
second_title: مرجع API Aspose.Slides برای C++
description: عناصری یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب نزولی مرتب می‌کند.
type: docs
weight: 222
url: /fa/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) متد

عناصر یک دنباله را بر اساس مقادیر کلید انتخاب‌شده توسط keySelector به ترتیب نزولی مرتب می‌کند.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| keySelector | یک تابع برای استخراج یک کلید از یک عنصر. |

### مقدار بازگردانده شده

یک IOrderedEnumerable که عناصر آن بر اساس ترتیب نزولی کلید مرتب شده‌اند

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) متد


```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* کلاس [Func](../../../system/func/)
* کلاس [IEnumerable](../)
* فضای‌نام [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)