---
title: Delay()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างงานที่เสร็จสิ้นหลังจากการหน่วงเวลา
type: docs
weight: 105
url: /th/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) ฟังก์ชัน

สร้างงานที่เสร็จสิ้นหลังจากการหน่วงเวลา

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | จำนวนมิลลิวินาทีที่ต้องรอก่อนที่จะทำงานที่ส่งคืนเสร็จสิ้น, หรือ -1 เพื่อรอโดยไม่จำกัด |

### ค่าที่ส่งคืน

งานที่แทนการหน่วงเวลา

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) ฟังก์ชัน

สร้างงานที่เสร็จสิ้นหลังจากการหน่วงเวลาและสามารถยกเลิกได้

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | จำนวนมิลลิวินาทีที่ต้องรอก่อนที่จะทำงานที่ส่งคืนเสร็จสิ้น, หรือ -1 เพื่อรอโดยไม่จำกัด |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | โทเค็นการยกเลิกที่สามารถใช้เพื่อยกเลิกการหน่วงเวลา |

### ค่าที่ส่งคืน

งานที่แทนการหน่วงเวลา

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../system/taskptr/)
* คลาส [CancellationToken](../../system.threading/cancellationtoken/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)