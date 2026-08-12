---
title: Change()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดเวลาซ้ำหรือยกเลิกตัวจับเวลา.
type: docs
weight: 14
url: /th/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) เมธอด

กำหนดเวลาซ้ำหรือยกเลิกตัวจับเวลา.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) ก่อนการเรียกฟังก์ชัน callback ครั้งถัดไป, หน่วยเป็นมิลลิวินาที; ค่าติดลบจะยกเลิกตัวจับเวลาแม้ว่าจะถูกกำหนดไว้ |
| period | **int64_t** | [Timeout](../../timeout/) ระหว่างการเรียกฟังก์ชัน callback อย่างต่อเนื่อง, หน่วยเป็นมิลลิวินาที; ค่าที่ไม่เป็นบวกหมายความว่าตัวจับเวลาจะทำงานเพียงครั้งเดียว |

## Timer::Change(System::TimeSpan, System::TimeSpan) เมธอด

กำหนดเวลาซ้ำหรือยกเลิกตัวจับเวลา.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ก่อนการเรียกฟังก์ชัน callback ครั้งถัดไป; ค่าติดลบจะยกเลิกตัวจับเวลาแม้ว่าจะถูกกำหนดไว้ |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ระหว่างการเรียกฟังก์ชัน callback อย่างต่อเนื่อง; ค่าที่ไม่เป็นบวกหมายความว่าตัวจับเวลาจะทำงานเพียงครั้งเดียว |

## ดูเพิ่มเติม

* คลาส [Timer](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)