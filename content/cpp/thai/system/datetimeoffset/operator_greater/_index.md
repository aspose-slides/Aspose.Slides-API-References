---
title: operator>()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดว่าตัวอ็อบเจกต์ปัจจุบันแทนค่าที่เป็นวันที่และเวลาที่อยู่หลังค่าที่แสดงโดยอ็อบเจกต์ DateTimeOffset ที่ระบุหรือไม่.
type: docs
weight: 573
url: /th/system/datetimeoffset/operator_greater/
---
## DateTimeOffset::operator>(const DateTimeOffset\&) const เมธอด

กำหนดว่าตัวอ็อบเจกต์ปัจจุบันแทนค่าที่เป็นวันที่และเวลาที่อยู่หลังค่าที่แทนโดยอ็อบเจกต์ [DateTimeOffset](../) ที่ระบุหรือไม่.

```cpp
bool System::DateTimeOffset::operator>(const DateTimeOffset &other) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | อ็อบเจกต์ [DateTimeOffset](../) เพื่อเปรียบเทียบกับตัวอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

True หากค่าที่เป็นวันที่และเวลาที่แสดงโดยตัวอ็อบเจกต์ปัจจุบันอยู่หลังค่าที่แสดงโดย **other** มิฉะนั้น - false

## DateTimeOffset::operator>(std::nullptr_t) const เมธอด

```cpp
constexpr bool System::DateTimeOffset::operator>(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [DateTimeOffset](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)