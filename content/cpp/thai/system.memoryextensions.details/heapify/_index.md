---
title: Heapify()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รักษาคุณสมบัติของ heap สำหรับคู่คีย์-ค่า.
type: docs
weight: 92
url: /th/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)> ) ฟังก์ชัน

รักษาคุณสมบัติของ heap สำหรับคู่คีย์-ค่า。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์ใน heap |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่าใน heap |
| n | **int32_t** | ขนาดของ heap |
| i | **int32_t** | [Index](../../system/index/) เพื่อทำ heapify จาก |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับคีย์ |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)