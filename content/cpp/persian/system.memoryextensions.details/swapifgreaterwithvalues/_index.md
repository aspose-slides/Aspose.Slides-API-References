---
title: SwapIfGreaterWithValues()
second_title: مرجع API Aspose.Slides برای C++
description: اگر شرط مقایسه برقرار باشد، جفت‌های کلید-مقدار را جابجا می‌کند.
type: docs
weight: 53
url: /fa/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) تابع

اگر شرط مقایسه برقرار باشد، جفت‌های کلید-مقدار را جابجا می‌کند.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | بازهٔ کلیدها |
| values | [Span](../../system/span/)\<TValue\>\& | بازهٔ مقادیر |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) تابع برای کلیدها |
| i | **int32_t** | اندیس اول برای مقایسه |
| j | **int32_t** | اندیس دوم برای مقایسه |

## موارد مرتبط

* کلاس [Span](../../system/span/)
* فضای نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)