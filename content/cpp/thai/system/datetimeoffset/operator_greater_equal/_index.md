---
title: operator>=()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าถาวรปัจจุบันแสดงค่าข้อมูลวันที่และเวลาที่อยู่หลังหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ DateTimeOffset ที่ระบุ
type: docs
weight: 599
url: /th/system/datetimeoffset/operator_greater_equal/
---
## DateTimeOffset::operator>=(const DateTimeOffset\&) const เมธอด

กำหนดว่าถาวรปัจจุบันแสดงค่าข้อมูลวันที่และเวลาที่อยู่หลังหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [DateTimeOffset](../) ที่ระบุ

```cpp
bool System::DateTimeOffset::operator>=(const DateTimeOffset &other) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | อ็อบเจกต์ [DateTimeOffset](../) ที่ใช้เปรียบเทียบกับอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งคืน

เป็นจริงหากค่าที่แสดงวันที่และเวลาของอ็อบเจกต์ปัจจุบันอยู่หลังหรือเท่ากับค่าที่แสดงโดย **other** มิฉะนั้นคือเท็จ

## DateTimeOffset::operator>=(std::nullptr_t) const เมธอด




```cpp
constexpr bool System::DateTimeOffset::operator>=(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [DateTimeOffset](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)