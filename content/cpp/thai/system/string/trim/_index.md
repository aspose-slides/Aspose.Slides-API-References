---
title: Trim()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบอักขระ whitespace ทั้งหมดออกจากส่วนต้นและส่วนท้ายของสตริง
type: docs
weight: 677
url: /th/system/string/trim/
---
## String::Trim() const เมธอด

ลบอักขระ whitespace ทั้งหมดออกจากส่วนต้นและส่วนท้ายของสตริง

```cpp
String System::String::Trim() const
```

### ค่าที่ส่งคืน

[String](../) ที่ไม่มี whitespace ที่จุดเริ่มหรือจุดสิ้นสุด

## String::Trim(char_t) const เมธอด

ลบอักขระที่ส่งเข้ามาทั้งหมดออกจากส่วนต้นและส่วนท้ายของสตริง

```cpp
String System::String::Trim(char_t ch) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char_t | สัญลักษณ์ที่จะลบ |

### ค่าที่ส่งคืน

ผลลัพธ์ของการลบ

## String::Trim(const String\&) const เมธอด

ลบอักขระที่ส่งเข้ามาทั้งหมดออกจากส่วนต้นและส่วนท้ายของสตริง

```cpp
String System::String::Trim(const String &anyOf) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) ของอักขระที่จะลบ |

### ค่าที่ส่งคืน

[String](../) ที่ไม่มีอักขระที่ถูกลบ

## String::Trim(const ArrayPtr\<char_t\>\&) const เมธอด

ลบอักขระที่ส่งเข้ามาทั้งหมดออกจากส่วนต้นและส่วนท้ายของสตริง

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่จะลบ |

### ค่าที่ส่งคืน

[String](../) ที่ไม่มีอักขระที่ถูกลบ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)