---
title: ConstrainedCopy()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: ينسخ نطاقًا من العناصر من System.Array بدءًا من المصدر المحدد.
type: docs
weight: 716
url: /ar/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

ينسخ نطاقًا من العناصر من [System.Array](../) يبدأ من المصدر المحدد.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | نوع العناصر في مصفوفة المصدر |
| DstType | نوع العناصر في مصفوفة الوجهة |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | مصفوفة المصدر |
| srcIndex | **int64_t** | [Index](../../index/) في مصفوفة المصدر يحدد بداية نطاق العناصر للنسخ |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | مصفوفة الوجهة |
| dstIndex | **int64_t** | [Index](../../index/) في مصفوفة الوجهة لبدء إدراج العناصر المنسوخة عند |
| count | **int64_t** | عدد العناصر للنسخ |

## Remarks

تنفيذ مبدئي خام دون أي إكمال!

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)