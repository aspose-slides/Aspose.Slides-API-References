---
title: HeapSort()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفذ فرزًا هيكليًا على أزواج المفتاح والقيمة.
type: docs
weight: 79
url: /ar/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) دالة

تنفذ فرزًا هيكليًا على أزواج المفتاح والقيمة.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | نطاق المفاتيح للفرز |
| values | [Span](../../system/span/)\<TValue\>\& | نطاق القيم للفرز |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |

## انظر أيضًا

* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions::Details](../)
* المكتبة [Aspose.Slides](../../)