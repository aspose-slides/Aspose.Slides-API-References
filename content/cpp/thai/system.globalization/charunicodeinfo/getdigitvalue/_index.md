---
title: GetDigitValue()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับค่าตัวเลขของอักขระที่ระบุ.
type: docs
weight: 14
url: /th/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) เมธอด

รับค่าตัวเลขของอักขระที่ระบุ.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char16_t | อักขระ Unicode. |

### ค่าที่คืน

ค่าตัวเลขหรือ -1 หากอักขระที่ระบุไม่ใช่ตัวเลข.

## CharUnicodeInfo::GetDigitValue(const String\&, int) เมธอด

รับค่าตัวเลขของอักขระที่ตำแหน่งที่ระบุของสตริง.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่มีอักขระ Unicode. |
| index | int | ดัชนีของอักขระ Unicode. |

### ค่าที่คืน

ค่าตัวเลขหรือ -1 หากอักขระที่ระบุไม่ใช่ตัวเลข.

## ดูเพิ่มเติม

* คลาส [CharUnicodeInfo](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)