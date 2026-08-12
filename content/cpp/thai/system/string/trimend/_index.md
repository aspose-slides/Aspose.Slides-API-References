---
title: TrimEnd()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: ลบอักขระเว้นว่างทั้งหมดจากส่วนท้ายของสตริง.
type: docs
weight: 703
url: /th/system/string/trimend/
---
## String::TrimEnd() const เมธอด

ลบอักขระเว้นว่างทั้งหมดจากส่วนสุดท้ายของสตริง.

```cpp
String System::String::TrimEnd() const
```

### ค่าที่ส่งคืน

[String](../) โดยไม่มีเว้นว่างที่ต้น.

## String::TrimEnd(char_t) const เมธอด

ลบการเกิดขึ้นทั้งหมดของอักขระที่ส่งเข้ามาจากส่วนสุดท้ายของสตริง.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | สัญลักษณ์ที่จะลบ. |

### ค่าที่ส่งคืน

ผลลัพธ์การลบ.

## String::TrimEnd(const String\&) const เมธอด

ลบการเกิดขึ้นทั้งหมดของอักขระที่ส่งเข้ามาจากส่วนสุดท้ายของสตริง.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) ของอักขระที่จะลบ. |

### ค่าที่ส่งคืน

[String](../) โดยไม่มีอักขระที่ถูกลบ.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const เมธอด

ลบการเกิดขึ้นทั้งหมดของอักขระที่ส่งเข้ามาจากส่วนสุดท้ายของสตริง.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่จะลบ. |

### ค่าที่ส่งคืน

[String](../) โดยไม่มีอักขระที่ถูกลบ.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)