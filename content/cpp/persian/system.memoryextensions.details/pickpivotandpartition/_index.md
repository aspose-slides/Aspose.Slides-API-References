---
title: PickPivotAndPartition()
second_title: Aspose.Slides برای C++ مرجع API
description: محور را انتخاب می‌کند و جفت‌های کلید-مقدار را برای quicksort تقسیم می‌نماید.
type: docs
weight: 105
url: /fa/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) تابع

یک محور را انتخاب می‌کند و جفت‌های کلید-مقدار را برای quicksort تقسیم می‌نماید.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | بازه‌ای از کلیدها برای تقسیم |
| values | [Span](../../system/span/)\<TValue\>\& | بازه‌ای از مقادیر برای تقسیم |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |

### مقدار بازگشتی

اندیس محور پس از تقسیم

## موارد مرتبط

* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)