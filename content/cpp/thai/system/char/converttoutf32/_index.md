---
title: ConvertToUtf32()
second_title: Aspose.Slides สำหรับ API ของ C++
description: แปลงคู่ surrogate UTF-16 ที่ระบุเป็นหน่วยรหัส UTF-32.
type: docs
weight: 287
url: /th/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) เมธอด

แปลงคู่ surrogate UTF-16 ที่ระบุเป็นหน่วยรหัส UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| highSurrogate | char_t | ส่วนสูงของคู่ surrogate UTF-16 ที่จะถูกแปลง |
| lowSurrogate | char_t | ส่วนต่ำของคู่ surrogate UTF-16 ที่จะถูกแปลง |

### ค่าที่ส่งคืน

หน่วยรหัส UTF-32 ที่ได้จากการแปลง

## Char::ConvertToUtf32(const String\&, int) เมธอด

แปลงค่าของอักขระหรือคู่ surrogate ที่เข้ารหัสเป็น UTF-16 ณ ตำแหน่งที่ระบุในสตริงเป็นหน่วยรหัส UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../string/)\& | สตริงที่มีอักขระหรือคู่ surrogate |
| index | int | ตำแหน่งดัชนีของอักขระหรือคู่ surrogate ในสตริงที่ระบุ |

### ค่าที่ส่งคืน

หน่วยรหัส UTF-32 ที่ได้จากการแปลง

## ดูเพิ่มเติม

* คลาส [Char](../)
* คลาส [String](../../string/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)