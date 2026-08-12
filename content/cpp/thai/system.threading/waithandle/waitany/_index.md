---
title: WaitAny()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนแฮนด์เลอร์ใด ๆ ทำงาน.
type: docs
weight: 14
url: /th/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) เมธอด


รอจนแฮนด์เลอร์ใด ๆ ทำงาน.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | แฮนด์เลอร์ที่ต้องรอ |
| millisecondsTimeout | int | [Timeout](../../timeout/) ที่ต้องรอ, หน่วยเป็นมิลลิวินาที; -1 หมายถึงการรอไม่สิ้นสุด, 0 หมายถึงตรวจสอบแล้วคืนค่า, ค่าบวกหมายถึงการหมดเวลา |

### ค่าที่คืน

คืนค่า true หากแฮนด์เลอร์ใดทำงาน, false หากเกินเวลาที่กำหนด.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) เมธอด


รอจนแฮนด์เลอร์ใด ๆ ทำงาน.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | แฮนด์เลอร์ที่ต้องรอ |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) ที่แสดงจำนวนมิลลิวินาทีที่ต้องรอ, หรือ [System::TimeSpan](../../../system/timespan/) ที่แสดง -1 มิลลิวินาทีเพื่อรอโดยไม่จำกัดเวลา |

### ค่าที่คืน

คืนค่า true หากแฮนด์เลอร์ใดทำงาน, false หากเกินเวลาที่กำหนด.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) เมธอด


รอจนแฮนด์เลอร์ใด ๆ ทำงาน.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | แฮนด์เลอร์ที่ต้องรอ |

### ค่าที่คืน

คืนค่า true เมื่อทุกองค์ประกอบใน waitHandles ได้รับสัญญาณ; มิฉะนั้นเมธอดจะไม่คืนค่า.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [WaitHandle](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)