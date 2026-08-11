---
title: LINQ_Select()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر یک توالی را تبدیل می‌کند.
type: docs
weight: 248
url: /fa/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method

Transforms elements of a sequence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقداری که توسط **selector** برگردانده می‌شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | یک تابع تبدیل. |

### مقدار بازگشت

یک [IEnumerable](../) که عناصر بازگردانده‌شده توسط تابع **selector** را شامل می‌شود.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method

Transforms each element of a sequence into a new form by incorporating the element's index.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقداری که توسط **selector** برگردانده می‌شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | یک تابع تبدیل. |

### مقدار بازگشت

یک [IEnumerable](../) که عناصر بازگردانده‌شده توسط تابع **selector** را شامل می‌شود.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IEnumerable](../)
* کلاس [Func](../../../system/func/)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)