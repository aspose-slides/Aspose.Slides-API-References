---
title: operator>=()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าช่วงเวลาที่อ็อบเจกต์ปัจจุบันแสดงอยู่ยาวกว่า หรือเท่ากับช่วงเวลาที่อ็อบเจกต์ที่ระบุแสดงหรือไม่.
type: docs
weight: 417
url: /th/system/timespan/operator_greater_equal/
---
## TimeSpan::operator>=(TimeSpan) const เมธอด

กำหนดว่าช่วงเวลาที่อ็อบเจกต์ปัจจุบันแสดงอยู่ยาวกว่า หรือเท่ากับช่วงเวลาที่อ็อบเจกต์ที่ระบุแสดงหรือไม่.

```cpp
constexpr bool System::TimeSpan::operator>=(TimeSpan value) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [TimeSpan](../) | อ็อบเจกต์ [TimeSpan](../) เพื่อเปรียบเทียบกับอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

True ถ้าเวลาช่วงที่แสดงโดยอ็อบเจกต์ปัจจุบันยาวกว่า หรือเท่ากับเวลาช่วงที่แสดงโดย **value**, มิฉะนั้น - false

## TimeSpan::operator>=(std::nullptr_t) const เมธอด

```cpp
constexpr bool System::TimeSpan::operator>=(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [TimeSpan](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)