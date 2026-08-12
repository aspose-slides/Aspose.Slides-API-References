---
title: BinarySearchImpl()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: การทำงานค้นหาแบบไบนารีทั่วไป.
type: docs
weight: 118
url: /th/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) ฟังก์ชัน

การทำงานค้นหาแบบไบนารีทั่วไป.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Type of elements in span |
| TValue | Type of value to search for |
| TCompareFunc | Function type for comparison |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value | const TValue\& | ค่าที่ต้องการค้นหา |
| compareFunc | TCompareFunc | ฟังก์ชันที่เปรียบเทียบค่ากับองค์ประกอบของสแปนและส่งคืน **int32_t** (-1, 0, 1) |

### ค่าที่ส่งคืน

[Index](../../system/index/) ขององค์ประกอบที่พบหรือส่วนเติมเต็มแบบบิตของตำแหน่งแทรก

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)