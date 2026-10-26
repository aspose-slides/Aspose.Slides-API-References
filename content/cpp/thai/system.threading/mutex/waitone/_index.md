---
title: WaitOne()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ล็อก mutex. ทำการรอโดยไม่จำกัดหากจำเป็น.
type: docs
weight: 53
url: /th/system.threading/mutex/waitone/
---
## Mutex::WaitOne() เมธอด

ล็อก mutex. ทำการรอโดยไม่จำกัดหากจำเป็น.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### ค่าที่ส่งคืน

จะคืนค่า true เสมอเพราะจะไม่คืนค่าจนกว่า mutex จะถูกล็อก

## Mutex::WaitOne(int) เมธอด

ล็อก mutex. ทำการรอหากจำเป็น.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| millisecondsTimeout | int | ระยะเวลาเวลารอในหน่วยมิลลิวินาที |

### ค่าที่ส่งคืน

คืนค่า true หาก mutex ถูกล็อกหรือ false หากเวลาที่กำหนดหมด

## Mutex::WaitOne(TimeSpan) เมธอด

ล็อก mutex. ทำการรอหากจำเป็น.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) ที่ระบุจำนวนมิลลิวินาทีที่ต้องรอ หรือ [System::TimeSpan](../../../system/timespan/) ที่ระบุ -1 มิลลิวินาทีเพื่อรอโดยไม่จำกัด |

### ค่าที่ส่งคืน

คืนค่า true หาก mutex ถูกล็อกหรือ false หากเวลาที่กำหนดหมด

## ดูเพิ่มเติม

* คลาส [Mutex](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)