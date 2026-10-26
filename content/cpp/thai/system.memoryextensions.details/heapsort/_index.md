---
title: HeapSort()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการ heap sort บนคู่คีย์-ค่า.
type: docs
weight: 79
url: /th/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) ฟังก์ชัน

ทำการเรียงลำดับแบบ heap sort บนคู่คีย์-ค่า.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์ที่ต้องเรียงลำดับ |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่าที่ต้องเรียงลำดับ |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับคีย์ |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)