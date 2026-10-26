---
title: FlushAsync()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบคำขอยกเลิก.
type: docs
weight: 157
url: /th/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) เมธอด


ทำการล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบคำขอยกเลิก.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเคนที่ใช้สำหรับตรวจสอบคำขอยกเลิก. |

### ค่าที่ส่งกลับ

งานที่แสดงถึงการทำงานล้างแบบอะซิงโครนัส.

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* คลาส [CancellationToken](../../../system.threading/cancellationtoken/)
* คลาส [FileStream](../)
* เนมส페ซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)