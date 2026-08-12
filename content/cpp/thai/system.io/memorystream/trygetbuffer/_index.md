---
title: TryGetBuffer()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าอาเรย์ของไบต์ที่ไม่มีเครื่องหมายซึ่งสตรีมนี้ถูกสร้างขึ้นจาก.
type: docs
weight: 170
url: /th/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) เมธอด

คืนค่าอาเรย์ของไบต์ที่ไม่มีเครื่องหมายจากซึ่งสตรีมนี้ถูกสร้างขึ้น

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ - พารามิเตอร์ out. เมื่อเมธอดนี้คืนค่า true, ส่วนของอาร์เรย์ไบต์ที่ใช้สร้างสตรีมนี้; เมื่อเมธอดนี้คืนค่า false, พารามิเตอร์นี้จะตั้งเป็นค่า default. |

### ค่าที่ส่งคืน

true หากการแปลงสำเร็จ

## ดูเพิ่มเติม

* คลาส [ArraySegment](../../../system/arraysegment/)
* คลาส [MemoryStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)