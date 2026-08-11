---
title: InsertionSort()
second_title: Aspose.Slides لمرجع API C++
description: يقوم بفرز الإدراج على أزواج المفتاح-القيمة.
type: docs
weight: 66
url: /ar/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) دالة

يُجري فرز الإدراج على أزواج المفتاح-القيمة.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### معامل القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | نطاق المفاتيح للترتيب |
| values | [Span](../../system/span/)\<TValue\>\& | نطاق القيم للترتيب |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |

## انظر أيضًا

* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions::Details](../)
* مكتبة [Aspose.Slides](../../)