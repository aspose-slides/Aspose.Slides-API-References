---
title: WaitAll()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รอให้ตัวจัดการทั้งหมดทำงาน.
type: docs
weight: 1
url: /th/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) เมธอด

รอให้ทุก handle ทำงานเสร็จ

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle ที่ต้องรอ |
| millisecondsTimeout | int | [Timeout](../../timeout/) ที่ต้องรอ, หน่วยเป็นมิลลิวินาที; -1 หมายถึงการรอไม่จำกัด, 0 หมายถึงตรวจสอบและคืนค่า, ค่าบวกเป็นเวลาหมดเวลา |

### ค่าที่ส่งกลับ

True หากทุก handle ถูกส่งสัญญาณ, false หากเวลาหมด

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) เมธอด

รอให้ทุก handle ทำงานเสร็จ

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle ที่ต้องรอ |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) ที่แสดงจำนวนมิลลิวินาทีที่ต้องรอ, หรือ [System::TimeSpan](../../../system/timespan/) ที่แสดง -1 มิลลิวินาทีเพื่อรออย่างไม่มีที่สิ้นสุด |

### ค่าที่ส่งกลับ

True หากทุก handle ถูกส่งสัญญาณ, false หากเวลาหมด

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) เมธอด

รอให้ทุก handle ทำงานเสร็จ

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle ที่ต้องรอ |

### ค่าที่ส่งกลับ

True เมื่อทุกองค์ประกอบใน waitHandles ได้รับสัญญาณ; มิฉะนั้นเมธอดจะไม่คืนค่า

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [WaitHandle](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)