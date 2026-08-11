---
title: LINQ_SelectMany()
second_title: Aspose.Slides برای C++ مرجع API
description: هر عنصر یک دنباله را پردازش می‌کند و توالی‌های حاصل را در یک دنباله ترکیب می‌نماید.
type: docs
weight: 300
url: /fa/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) متد

هر عنصر یک دنباله را پردازش می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌نماید.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ResultType | نوع مقدار برگشتی توسط **selector**. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | یک تابع تبدیل. |

### مقدار بازگشتی

یک [IEnumerable](../) که شامل نتیجه‌ی فراخوانی یک تابع پروژکشن یک-به-چند بر روی هر عنصر دنبالهٔ ورودی است.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) متد

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IEnumerable](../)
* کلاس [Func](../../../system/func/)
* فضای نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)