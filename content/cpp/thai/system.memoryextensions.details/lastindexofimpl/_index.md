---
title: LastIndexOfImpl()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหาดัชนีสุดท้ายของค่าหนึ่งในช่วง
type: docs
weight: 14
url: /th/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) ฟังก์ชัน

ค้นหาดัชนีสุดท้ายของค่าในช่วงหนึ่ง.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในช่วง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) เพื่อค้นหา |
| length | **int32_t** | ความยาวที่จะค้นหาใน |
| value | const T\& | ค่าที่ต้องการหา |

### ค่าที่คืนกลับ

ดัชนีสุดท้ายของค่าที่กำหนด, หรือ **-1** หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)