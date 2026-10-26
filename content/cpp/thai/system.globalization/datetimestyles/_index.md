---
title: DateTimeStyles
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดตัวเลือกการจัดรูปแบบวันที่และเวลา. บิตแฟล็ก.
type: docs
weight: 456
url: /th/system.globalization/datetimestyles/
---
## DateTimeStyles enum

กำหนดตัวเลือกการจัดรูปแบบวันที่และเวลา. บิตแฟล็ก.

```cpp
enum class DateTimeStyles : int32_t
```

### ค่า

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | ค่าเริ่มต้น. |
| AllowLeadingWhite | 1 | ละเว้นช่องว่างนำหน้า. |
| AllowTrailingWhite | 2 | ละเว้นช่องว่างต่อท้าย. |
| AllowInnerWhite | 4 | ละเว้นช่องว่างภายใน. |
| AllowWhiteSpaces | n/a | ละเว้นช่องว่างทั้งหมด. |
| NoCurrentDateDefault | 8 | เมื่อตีความสตริงวันที่/เวลา, หากปี/เดือน/วันทั้งหมดหายไป, ตั้งค่าวันที่เริ่มต้นเป็น 0001/1/1 แทนปี/เดือน/วันปัจจุบัน. |
| AdjustToUniversal | 16 | เมื่อตีความสตริงวันที่/เวลา, หากมีตัวระบุเขตเวลา (\"GMT\",\"Z\",\"+xxxx\",\"-xxxx\") เราจะปรับเวลาให้สอดคล้องกับ GMT. |
| AssumeLocal | 32 | หากไม่มีเขตเวลา, ใช้เขตเวลาท้องถิ่น. |
| AssumeUniversal | 64 | หากไม่มีเขตเวลา, ใช้ UTC. |
| RoundtripKind | 128 | พยายามรักษาว่าอินพุตเป็นไม่ระบุ, ท้องถิ่น หรือ UTC. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)