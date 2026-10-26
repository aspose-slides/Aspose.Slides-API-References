---
title: operator<=()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าปัจจุบันอ็อบเจกต์แสดงค่าที่เป็นวันและเวลา ที่เร็วกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ DateTimeOffset ที่ระบุ
type: docs
weight: 586
url: /th/system/datetimeoffset/operator_less_equal/
---
## DateTimeOffset::operator<=(const DateTimeOffset\&) const เมธอด

กำหนดว่าปัจจุบันอ็อบเจกต์แสดงค่าที่เป็นวันและเวลา ที่เร็วกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [DateTimeOffset](../) ที่ระบุ

```cpp
bool System::DateTimeOffset::operator<=(const DateTimeOffset &other) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | วัตถุ [DateTimeOffset](../) เพื่อเปรียบเทียบกับอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

True หากค่าที่เป็นวันและเวลาที่แสดงโดยอ็อบเจกต์ปัจจุบันเร็วกว่าหรือเท่ากับค่าที่แสดงโดย **other**, มิฉะนั้น - false

## DateTimeOffset::operator<=(std::nullptr_t) const เมธอด

```cpp
constexpr bool System::DateTimeOffset::operator<=(std::nullptr_t) const
```

## ดูเพิ่มเติม

* คลาส [DateTimeOffset](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)