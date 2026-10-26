---
title: Heapify()
second_title: Aspose.Slides برای C++ مرجع API
description: خواص پشته را برای جفت‌های کلید-مقدار حفظ می‌کند.
type: docs
weight: 92
url: /fa/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) تابع

خواص پشته را برای جفت‌های کلید-مقدار حفظ می‌کند.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقدارها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | بازه کلیدها در پشته |
| values | [Span](../../system/span/)\<TValue\>\& | بازه مقدارها در پشته |
| n | **int32_t** | اندازه پشته |
| i | **int32_t** | [Index](../../system/index/) برای heapify از |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |

## موارد دیگر

* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)