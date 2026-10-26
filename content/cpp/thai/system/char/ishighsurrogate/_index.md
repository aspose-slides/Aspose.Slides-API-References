---
title: IsHighSurrogate()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในสตริงที่กำหนดเป็นหน่วยรหัส UTF-16 high surrogate หรือไม่.
type: docs
weight: 40
url: /th/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) เมธอด

กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในสตริงที่กำหนดเป็นหน่วยรหัส UTF-16 high surrogate หรือไม่

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | สตริง |
| index | int | ดัชนีในสตริงที่กำหนดของอักขระที่จะทดสอบ |

### ค่าที่ส่งคืน

True หากตัวอักษรที่ตำแหน่งที่ระบุเป็นหน่วยรหัส UTF-16 high surrogate, มิฉะนั้น - false

## Char::IsHighSurrogate(const char_t *, int) เมธอด

กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่กำหนดเป็น high surrogate หรือไม่

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const char_t * | ตัวชี้ไปยังจุดเริ่มต้นของบัฟเฟอร์อักขระ |
| idx | int | ดัชนีศูนย์ฐานในบัฟเฟอร์ที่กำหนดของอักขระที่จะทดสอบ |

### ค่าที่ส่งคืน

True หากตัวอักษรที่ตำแหน่งที่ระบุเป็น high surrogate, มิฉะนั้น - false

## Char::IsHighSurrogate(char_t) เมธอด

กำหนดว่าตัวอักษรที่ระบุเป็น high surrogate หรือไม่

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่จะทดสอบ |

### ค่าที่ส่งคืน

True หากตัวอักษรที่ระบุเป็น high surrogate, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* คลาส [Char](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)