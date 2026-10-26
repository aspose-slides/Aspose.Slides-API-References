---
title: PickPivotAndPartition()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เลือก pivot และแบ่งคู่คีย์-ค่าเพื่อ quicksort.
type: docs
weight: 105
url: /th/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function

เลือก pivot และแบ่งคู่คีย์-ค่าเพื่อ quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์สำหรับการแบ่ง |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่สำหรับการแบ่ง |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับคีย์ |

### Return Value

ดัชนี pivot หลังจากการแบ่ง

## See Also

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)