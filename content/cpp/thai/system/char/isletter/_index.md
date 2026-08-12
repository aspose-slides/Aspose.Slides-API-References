---
title: IsLetter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่กำหนดนั้นเป็น Unicode letter หรือไม่.
type: docs
weight: 92
url: /th/system/char/isletter/
---
## Char::IsLetter(const char_t *, int) เมธอด

กำหนดว่าตัวอักษรที่ตำแหน่งที่ระบุในบัฟเฟอร์อักขระที่กำหนดนั้นเป็นประเภท Unicode letter หรือไม่.

```cpp
static bool System::Char::IsLetter(const char_t *str, int idx)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const char_t * | ตัวชี้ไปยังจุดเริ่มต้นของบัฟเฟอร์อักขระ |
| idx | int | ดัชนีเริ่มจากศูนย์ในบัฟเฟอร์ที่ระบุของตัวอักษรที่ต้องการทดสอบ |

### ค่ารีเทิร์น

คืนค่า true ถ้าตัวอักษรที่ตำแหน่งที่ระบุเป็น Unicode letter, มิฉะนั้น - false

## Char::IsLetter(char_t) เมธอด

กำหนดว่าตัวอักษรที่ระบุเป็นประเภท Unicode letter หรือไม่.

```cpp
static bool System::Char::IsLetter(char_t c)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ตัวอักษรที่ต้องการทดสอบ |

### ค่ารีเทิร์น

คืนค่า true ถ้าตัวอักษรที่ระบุเป็น Unicode letter, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Char](../)
* เนมสเปส [System](../../)
* ไลบรารี [Aspose.Slides](../../../)