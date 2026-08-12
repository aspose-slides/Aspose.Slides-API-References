---
title: IsLowSurrogate()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่กำหนดเป็น low surrogate หรือไม่
type: docs
weight: 53
url: /th/system/char/islowsurrogate/
---
## Char::IsLowSurrogate(const char_t *, int) เมธอด

กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่กำหนดเป็น low surrogate หรือไม่

```cpp
static bool System::Char::IsLowSurrogate(const char_t *str, int idx)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const char_t * | ตัวชี้ไปยังจุดเริ่มต้นของบัฟเฟอร์อักขระ |
| idx | int | ดัชนีที่เริ่มจากศูนย์ในบัฟเฟอร์ที่ระบุของอักขระที่ต้องการทดสอบ |

### ค่าที่คืน

true หากตัวอักษรที่ตำแหน่งที่ระบุเป็น low surrogate, มิฉะนั้น - false

## Char::IsLowSurrogate(char_t) เมธอด

กำหนดว่าตัวอักษรที่ระบุเป็น low surrogate หรือไม่

```cpp
static bool System::Char::IsLowSurrogate(char_t c)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | อักขระที่ต้องการทดสอบ |

### ค่าที่คืน

true หากตัวอักษรที่ระบุเป็น low surrogate, มิฉะนั้น - false

## ดูเพิ่ม

* คลาส [Char](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)