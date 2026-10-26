---
title: GetDecimalDigitValue()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับค่าตัวเลขฐานสิบของอักขระที่ระบุ
type: docs
weight: 1
url: /th/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) เมธอด

รับค่าตัวเลขฐานสิบของอักขระที่ระบุ

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char16_t | อักขระยูนิโค้ด |

### ค่าที่คืน

ค่าตัวเลขฐานสิบ หรือ -1 หากอักขระที่ระบุไม่ใช่ตัวเลขฐานสิบ

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) เมธอด

รับค่าตัวเลขฐานสิบของอักขระที่ตำแหน่งที่ระบุในสตริง

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่มีอักขระยูนิโค้ด |
| index | int | ตำแหน่งของอักขระยูนิโค้ด |

### ค่าที่คืน

ค่าตัวเลขฐานสิบ หรือ -1 หากอักขระที่ระบุไม่ใช่ตัวเลขฐานสิบ

## ดูเพิ่มเติม

* คลาส [CharUnicodeInfo](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)