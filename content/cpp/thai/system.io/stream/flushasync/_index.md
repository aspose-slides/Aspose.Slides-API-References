---
title: FlushAsync()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำงานแบบอะซิงโครนัสเพื่อเคลียร์บัฟเฟอร์ทั้งหมดของสตรีมนี้, ทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบการร้องขอยกเลิก.
type: docs
weight: 118
url: /th/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) เมธอด

ทำงานแบบอะซิงโครนัสเพื่อเคลียร์บัฟเฟอร์ทั้งหมดของสตรีมนี้, ทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบการร้องขอยกเลิก.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเค็นที่ใช้ตรวจสอบการร้องขอยกเลิก. |

### ค่าที่คืนกลับ

งานที่แสดงถึงการทำ flush แบบอะซิงโครนัส

## Stream::FlushAsync() เมธอด

ทำงานแบบอะซิงโครนัสเพื่อเคลียร์บัฟเฟอร์ทั้งหมดของสตรีมนี้, ทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบการร้องขอยกเลิก.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### ค่าที่คืนกลับ

งานที่แสดงถึงการทำ flush แบบอะซิงโครนัส

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* คลาส [CancellationToken](../../../system.threading/cancellationtoken/)
* คลาส [Stream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)