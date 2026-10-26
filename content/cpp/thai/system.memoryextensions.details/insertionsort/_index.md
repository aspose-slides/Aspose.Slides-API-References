---
title: InsertionSort()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ทำการเรียงลำดับแบบ insertion sort บนคู่คีย์-ค่า.
type: docs
weight: 66
url: /th/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) ฟังก์ชัน

ดำเนินการเรียงลำดับแบบ insertion sort บนคู่คีย์-ค่า.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์ที่จะเรียงลำดับ |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่าที่จะเรียงลำดับ |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับคีย์ |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)