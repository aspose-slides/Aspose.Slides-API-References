---
title: LINQ_Min()
second_title: مرجع API Aspose.Slides برای C++
description: یک تابع تبدیل را بر روی هر عنصر از یک توالی عمومی اعمال می‌کند و کمینه مقدار حاصل را برمی‌گرداند.
type: docs
weight: 339
url: /fa/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) متد

یک تابع تبدیل را بر روی هر عنصر از یک توالی عمومی اعمال می‌کند و کمینه مقدار حاصل را برمی‌گرداند.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقداری که توسط selector برگردانده می‌شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | یک تابع تبدیل برای اعمال بر هر عنصر. |

### مقدار بازگشت

کمینه مقدار در توالی.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) متد

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## موارد مرتبط

* کلاس [Func](../../../system/func/)
* کلاس [IEnumerable](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)