---
title: InsertionSort()
second_title: مرجع API Aspose.Slides برای C++
description: مرتب‌سازی درجی را بر روی جفت‌های کلید-مقدار اجرا می‌کند.
type: docs
weight: 66
url: /fa/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) تابع

مرتب‌سازی درجی را بر روی جفت‌های کلید-مقدار اجرا می‌کند.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | بازه‌ای از کلیدها برای مرتب‌سازی |
| values | [Span](../../system/span/)\<TValue\>\& | بازه‌ای از مقادیر برای مرتب‌سازی |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |

## مراجعه به

* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)