---
title: operator<()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าช่วงเวลาที่อ็อบเจกต์ปัจจุบันแทนมีระยะเวลาสั้นกว่าช่วงเวลาที่อ็อบเจกต์ที่ระบุหรือไม่
type: docs
weight: 378
url: /th/system/timespan/operator_less/
---
## TimeSpan::operator<(TimeSpan) const เมธอด

กำหนดว่าช่วงเวลาที่อ็อบเจกต์ปัจจุบันแทนมีระยะเวลาสั้นกว่าช่วงเวลาที่อ็อบเจกต์ที่ระบุหรือไม่

```cpp
constexpr bool System::TimeSpan::operator<(TimeSpan value) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [TimeSpan](../) | อ็อบเจกต์ [TimeSpan](../) เพื่อเปรียบเทียบกับอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

True หากช่วงเวลาที่อ็อบเจกต์ปัจจุบันแทนมีระยะเวลาสั้นกว่าช่วงเวลาที่แทนโดย **value**, มิฉะนั้น - false

## TimeSpan::operator<(std::nullptr_t) const เมธอด




```cpp
constexpr bool System::TimeSpan::operator<(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [TimeSpan](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)