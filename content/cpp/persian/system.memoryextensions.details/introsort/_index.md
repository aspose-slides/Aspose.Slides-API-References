---
title: IntroSort()
second_title: Aspose.Slides برای C++ مرجع API
description: پیاده‌سازی داخلی الگوریتم اینترسورت برای جفت‌های کلید-مقدار.
type: docs
weight: 40
url: /fa/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) تابع

پیاده‌سازی داخلی الگوریتم اینترسورت برای جفت‌های کلید-مقدار.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| depthLimit | **int32_t** | حداکثر عمق بازگشت قبل از تغییر به هپ‌سورت |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |

## موارد مرتبط

* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)