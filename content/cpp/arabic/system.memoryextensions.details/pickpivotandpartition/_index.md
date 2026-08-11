---
title: PickPivotAndPartition()
second_title: Aspose.Slides لمرجع API C++
description: يختار المحور ويقسم أزواج المفتاح والقيمة للفرز السريع.
type: docs
weight: 105
url: /ar/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) دالة

يختار المحور ويقسم أزواج المفتاح والقيمة للفرز السريع.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| TKey | نوع المفاتيح |
| TValue | نوع القيم |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | المجال الخاص بالمفاتيح للتقسيم |
| values | [Span](../../system/span/)\<TValue\>\& | المجال الخاص بالقيم للتقسيم |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) دالة للمفاتيح |

### قيمة الإرجاع

فهرس المحور بعد التقسيم

## انظر أيضًا

* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions::Details](../)
* المكتبة [Aspose.Slides](../../)