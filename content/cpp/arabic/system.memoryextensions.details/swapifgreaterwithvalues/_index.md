---
title: SwapIfGreaterWithValues()
second_title: دليل API الخاص بـ Aspose.Slides للغة C++
description: يستبدل أزواج المفتاح والقيمة إذا تم استيفاء شرط المقارنة.
type: docs
weight: 53
url: /ar/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) دالة

يستبدل أزواج المفتاح والقيمة إذا تم استيفاء شرط المقارنة.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### معاملات

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | مجموعة المفاتيح |
| values | [Span](../../system/span/)\<TValue\>\& | مجموعة القيم |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |
| i | **int32_t** | الفهرس الأول للمقارنة |
| j | **int32_t** | الفهرس الثاني للمقارنة |

## أنظر أيضاً

* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions::Details](../)
* مكتبة [Aspose.Slides](../../)