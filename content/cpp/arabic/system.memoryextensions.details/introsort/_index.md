---
title: IntroSort()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تنفيذ داخلي لخوارزمية introsort لأزواج المفتاح والقيمة.
type: docs
weight: 40
url: /ar/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) دالة

تنفيذ داخلي لخوارزمية introsort لأزواج المفتاح والقيمة.
```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | نطاق keys للترتيب |
| values | [Span](../../system/span/)\<TValue\>\& | نطاق values للترتيب |
| depthLimit | **int32_t** | أقصى عمق للتكرار قبل التحويل إلى heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |

## انظر أيضًا

* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions::Details](../)
* مكتبة [Aspose.Slides](../../)