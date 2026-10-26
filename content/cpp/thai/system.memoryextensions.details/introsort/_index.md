---
title: IntroSort()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: การดำเนินการภายในของอัลกอริธึม introsort สำหรับคู่คีย์-ค่า.
type: docs
weight: 40
url: /th/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) ฟังก์ชัน


การทำงานภายในของอัลกอริธึม introsort สำหรับคู่คีย์-ค่า

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์ที่ต้องการจัดเรียง |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่าที่ต้องการจัดเรียง |
| depthLimit | **int32_t** | ความลึกสูงสุดของการเรียกซ้ำก่อนสลับไปใช้ heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | ฟังก์ชัน [Comparison](../../system/comparison/) สำหรับคีย์ |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)