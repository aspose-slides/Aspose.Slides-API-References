---
title: GetNumericValue()
second_title: Aspose.Slides สำหรับ C++ คู่มืออ้างอิง API
description: รับค่าตัวเลขที่เกี่ยวข้องกับอักขระที่ระบุ
type: docs
weight: 27
url: /th/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) เมธอด


รับค่าตัวเลขที่เกี่ยวข้องกับอักขระที่ระบุ.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char16_t | อักขระ Unicode |

### ค่าที่ส่งกลับ

ค่าตัวเลขหรือ -1 หากอักขระที่ระบุไม่ใช่อักขระตัวเลข.

## CharUnicodeInfo::GetNumericValue(const String\&, int) เมธอด


รับค่าตัวเลขที่เกี่ยวข้องกับอักขระที่ตำแหน่งที่ระบุในสตริง.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่มีอักขระ Unicode |
| index | int | ดัชนีของอักขระ Unicode |

### ค่าที่ส่งกลับ

ค่าตัวเลขหรือ -1 หากอักขระที่ระบุไม่ใช่อักขระตัวเลข.

## ดูเพิ่มเติม

* คลาส [CharUnicodeInfo](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)