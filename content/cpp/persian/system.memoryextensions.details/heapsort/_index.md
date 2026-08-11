---
title: HeapSort()
second_title: مرجع API Aspose.Slides برای C++
description: مرتب‌سازی heap sort بر روی جفت‌های کلید-مقدار انجام می‌شود.
type: docs
weight: 79
url: /fa/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) تابع


مرتب‌سازی heap sort بر روی جفت‌های کلید-مقدار انجام می‌شود.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | بازه‌ای از کلیدها برای مرتب‌سازی |
| values | [Span](../../system/span/)\<TValue\>\& | بازه‌ای از مقادیر برای مرتب‌سازی |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |

## موارد مرتبط

* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)