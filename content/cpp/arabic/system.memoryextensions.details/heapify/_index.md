---
title: Heapify()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحافظ على خاصية الكومة لأزواج المفتاح والقيمة.
type: docs
weight: 92
url: /ar/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) دالة

يحافظ على خاصية الكومة لأزواج المفتاح والقيمة.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | نطاق المفاتيح في الكومة |
| values | [Span](../../system/span/)\<TValue\>\& | نطاق القيم في الكومة |
| n | **int32_t** | حجم الكومة |
| i | **int32_t** | [Index](../../system/index/) للتهيئة من |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |

## انظر أيضًا

* فئة [Span](../../system/span/)
* مساحة الاسم [System::MemoryExtensions::Details](../)
* مكتبة [Aspose.Slides](../../)