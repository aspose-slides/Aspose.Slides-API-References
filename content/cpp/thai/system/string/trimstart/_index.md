---
title: TrimStart()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ลบอักขระช่องว่างทั้งหมดออกจากจุดเริ่มต้นของสตริง.
type: docs
weight: 690
url: /th/system/string/trimstart/
---
## String::TrimStart() const เมธอด

ลบอักขระช่องว่างทั้งหมดออกจากจุดเริ่มต้นของสตริง

```cpp
String System::String::TrimStart() const
```

### ค่าที่ส่งกลับ

[String](../) โดยไม่มีอักขระช่องว่างที่จุดเริ่มต้น

## String::TrimStart(char_t) const เมธอด

ลบการปรากฏทั้งหมดของอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นของสตริง

```cpp
String System::String::TrimStart(char_t ch) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char_t | สัญลักษณ์ที่จะลบ |

### ค่าที่ส่งกลับ

ผลลัพธ์การลบ

## String::TrimStart(const String\&) const เมธอด

ลบการปรากฏทั้งหมดของอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นของสตริง

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) ของอักขระที่จะลบ |

### ค่าที่ส่งกลับ

[String](../) โดยไม่มีอักขระที่ถูกลบ

## String::TrimStart(const ArrayPtr\<char_t\>\&) const เมธอด

ลบการปรากฏทั้งหมดของอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นของสตริง

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่จะลบ |

### ค่าที่ส่งกลับ

[String](../) โดยไม่มีอักขระที่ถูกลบ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)