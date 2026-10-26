---
title: Compare()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบสตริง ไม่ได้ดำเนินการ
type: docs
weight: 66
url: /th/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const เมธอด

เปรียบเทียบสตริง ไม่ได้ดำเนินการ

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | LHS string. |
| string2 | const [String](../../../system/string/)\& | RHS string. |

### ค่าที่ส่งกลับ

ค่าติดลบหาก LHS string อยู่ก่อน RHS one, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const เมธอด

เปรียบเทียบสตริง รองรับเฉพาะโหมด Ordinal และ OrdinalIgnoreCase เท่านั้น

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | LHS string. |
| b | const [String](../../../system/string/)\& | RHS string. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison type. |

### ค่าที่ส่งกลับ

ค่าติดลบหาก LHS string อยู่ก่อน RHS one, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const เมธอด

เปรียบเทียบส่วนหนึ่งของสตริงกับส่วนหนึ่งของสตริงที่สอง ไม่ได้ดำเนินการ

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | ดัชนีเริ่มต้นของอักขระใน **string1**. |
| length1 | int | จำนวนอักขระใน **string1** ที่จะเปรียบเทียบ. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | ดัชนีเริ่มต้นของอักขระใน **string2**. |
| length2 | int | จำนวนอักขระใน **string2** ที่จะเปรียบเทียบ. |

### ค่าที่ส่งกลับ

ค่าติดลบหากส่วนของสตริงแรกอยู่ก่อนส่วนของสตริงที่สอง, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const เมธอด

เปรียบเทียบส่วนท้ายของสตริงกับส่วนท้ายของสตริงที่สองโดยใช้วิธีการเปรียบเทียบสตริง ไม่ได้ดำเนินการ

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | ดัชนีเริ่มต้นของอักขระใน **string1**. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | ดัชนีเริ่มต้นของอักขระใน **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison options. |

### ค่าที่ส่งกลับ

ค่าติดลบหากส่วนของสตริงแรกอยู่ก่อนส่วนของสตริงที่สอง, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## CompareInfo::Compare(const String\&, int, const String\&, int) const เมธอด

เปรียบเทียบส่วนท้ายของสตริงกับส่วนท้ายของสตริงที่สอง ไม่ได้ดำเนินการ

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | ดัชนีเริ่มต้นของอักขระใน **string1**. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | ดัชนีเริ่มต้นของอักขระใน **string2**. |

### ค่าที่ส่งกลับ

ค่าติดลบหากส่วนของสตริงแรกอยู่ก่อนส่วนของสตริงที่สอง, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const เมธอด

เปรียบเทียบส่วนหนึ่งของสตริงกับส่วนหนึ่งของสตริงที่สองโดยใช้วิธีการเปรียบเทียบสตริง ไม่ได้ดำเนินการ

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | First string. |
| offset1 | int | ดัชนีเริ่มต้นของอักขระใน **string1**. |
| length1 | int | จำนวนอักขระใน **string1** ที่จะเปรียบเทียบ. |
| string2 | const [String](../../../system/string/)\& | Second string. |
| offset2 | int | ดัชนีเริ่มต้นของอักขระใน **string2**. |
| length2 | int | จำนวนอักขระใน **string2** ที่จะเปรียบเทียบ. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) comparison options. |

### ค่าที่ส่งกลับ

ค่าติดลบหากส่วนของสตริงแรกอยู่ก่อนส่วนของสตริงที่สอง, ศูนย์หากตรงกัน, ค่าบวกในกรณีอื่น

## ดูเพิ่มเติม

* Enum [CompareOptions](../../compareoptions/)
* คลาส [String](../../../system/string/)
* คลาส [CompareInfo](../)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)