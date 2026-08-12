---
title: SequenceEqualImpl()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าช่วงสองช่วงเท่ากันหรือไม่โดยเริ่มจากตำแหน่งที่ระบุ
type: docs
weight: 27
url: /th/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) ฟังก์ชัน


ตรวจสอบว่าช่วงสองช่วงเท่ากันหรือไม่โดยเริ่มจากตำแหน่งที่ระบุ

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในช่วง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ช่วงแรก |
| start | const **int32_t** | ดัชนีเริ่มต้นในช่วงแรก |
| length | **int32_t** | จำนวนองค์ประกอบที่ต้องเปรียบเทียบ |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ช่วงที่สอง |

### ค่าที่ส่งกลับ

true if the specified ranges are equal, false otherwise

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)