---
title: operator<()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าวัตถุปัจจุบันแสดงค่าวันที่และเวลาที่เกิดก่อนค่าที่แสดงโดยวัตถุ DateTimeOffset ที่ระบุหรือไม่
type: docs
weight: 560
url: /th/system/datetimeoffset/operator_less/
---
## DateTimeOffset::operator<(const DateTimeOffset\&) const เมธอด

กำหนดว่าวัตถุปัจจุบันแสดงค่าวันและเวลาที่เกิดก่อนค่าที่แสดงโดยวัตถุ [DateTimeOffset](../) ที่ระบุหรือไม่.

```cpp
bool System::DateTimeOffset::operator<(const DateTimeOffset &other) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | วัตถุ [DateTimeOffset](../) ที่ใช้เปรียบเทียบกับวัตถุปัจจุบัน |

### ค่าที่ส่งกลับ

True หากค่าด้วยวันที่และเวลาที่วัตถุปัจจุบันแสดงอยู่เกิดก่อนค่าที่แสดงโดย **other** มิฉะนั้น - false

## DateTimeOffset::operator<(std::nullptr_t) const เมธอด

```cpp
constexpr bool System::DateTimeOffset::operator<(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [DateTimeOffset](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)