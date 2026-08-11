---
title: LINQ_Max()
second_title: Aspose.Slides برای C++ مرجع API
description: یک تابع تبدیل را بر روی هر عنصر از یک توالی عمومی اعمال می‌کند و بیشترین مقدار حاصل را برمی‌گرداند.
type: docs
weight: 352
url: /fa/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) متد


یک تابع تبدیل را بر روی هر عنصر از یک توالی عمومی اعمال می‌کند و بیشترین مقدار حاصل را برمی‌گرداند.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقدار برگردانده‌شده توسط انتخاب‌کننده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | یک تابع تبدیل برای اعمال بر هر عنصر. |

### مقدار بازگشت

بیشترین مقدار در توالی.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) متد




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## موارد مرتبط

* کلاس [Func](../../../system/func/)
* کلاس [IEnumerable](../)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)