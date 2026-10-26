---
title: IsSurrogatePair()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: กำหนดว่าตัวอักษรสองตัวที่ระบุเป็นคู่ surrogate ของ UTF-16 หรือไม่
type: docs
weight: 27
url: /th/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) เมธอด

กำหนดว่าตัวอักษรสองตัวที่ระบุเป็นคู่ surrogate ของ UTF-16 หรือไม่

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| highSurrogate | char_t | อักขระที่ถูกทดสอบว่าเป็น high surrogate |
| lowSurrogate | char_t | อักขระที่ถูกทดสอบว่าเป็น low surrogate |

### ค่าที่คืน

true หากตัวอักษรที่ระบุเป็น surrogate pair, มิฉะนั้น - false

## Char::IsSurrogatePair(const String\&, int) เมธอด

กำหนดว่าตัวอักษรสองตัวต่อเนื่องในบัฟเฟอร์อักขระที่ระบุเป็น surrogate pair หรือไม่

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../string/)\& | สตริง |
| index | int | ดัชนีเริ่มจากศูนย์ในบัฟเฟอร์ที่ระบุซึ่งเป็นตำแหน่งเริ่มต้นของลำดับอักขระที่ต้องการทดสอบ |

### ค่าที่คืน

true หากตัวอักษรที่ระบุเป็น surrogate pair, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Char](../)
* คลาส [String](../../string/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)