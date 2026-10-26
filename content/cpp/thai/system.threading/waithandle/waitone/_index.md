---
title: WaitOne()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รอให้แฮนเดิลทำงานโดยไม่มีระยะเวลาจำกัด.
type: docs
weight: 27
url: /th/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() วิธีการ

รอให้แฮนเดิลทำงานโดยไม่มีระยะเวลาจำกัด

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### ค่าที่ส่งคืน

จะส่งคืนค่า true เสมอเนื่องจากไม่มีการหมดเวลา

## WaitHandle::WaitOne(int) วิธีการ

รอให้แฮนเดิลทำงาน

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) เพื่อรอ, หน่วยมิลลิวินาที; -1 หมายถึงการรอไม่จำกัด, 0 หมายถึงตรวจสอบแล้วคืนค่า, ค่าบวกเป็นเวลาจำกัด |

### ค่าที่ส่งคืน

True หากแฮนเดิลทำงาน, false หากหมดเวลา

## WaitHandle::WaitOne(TimeSpan) วิธีการ

รอให้แฮนเดิลทำงาน

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) ที่แสดงจำนวนมิลลิวินาทีที่รอ, หรือ [System::TimeSpan](../../../system/timespan/) ที่แสดง -1 มิลลิวินาทีเพื่อรอโดยไม่มีที่สิ้นสุด |

### ค่าที่ส่งคืน

True หากแฮนเดิลทำงาน, false หากหมดเวลา

## WaitHandle::WaitOne(int, bool) วิธีการ

รอให้แฮนเดิลทำงาน

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) เพื่อรอ, หน่วยมิลลิวินาที; -1 หมายถึงการรอไม่จำกัด, 0 หมายถึงตรวจสอบแล้วคืนค่า, ค่าบวกเป็นเวลาจำกัด |
| exitContext | **bool** | หากเป็น true, การรอควรปลดล็อกบนแฮนเดิลก่อนทำการรอ |

### ค่าที่ส่งคืน

True หากแฮนเดิลทำงาน, false หากหมดเวลา

## ดูเพิ่มเติม

* คลาส [WaitHandle](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)