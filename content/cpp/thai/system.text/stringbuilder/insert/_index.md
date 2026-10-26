---
title: Insert()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกสตริงเข้าไปในตำแหน่งคงที่ของตัวสร้าง.
type: docs
weight: 183
url: /th/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) เมธอด


แทรกสตริงเข้าไปในตำแหน่งคงที่ของตัวสร้าง.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ตำแหน่งที่จะแทรกอักขระเข้าไป |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อแทรก |

### ค่าที่ส่งกลับ

This pointer.

## StringBuilder::Insert(int32_t, const String\&, int32_t) เมธอด


แทรกสตริงที่ทำซ้ำเข้าไปในตำแหน่งคงที่ของตัวสร้าง.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะแทรกอักขระเข้าไป |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อแทรก |
| count | **int32_t** | จำนวนครั้งที่ต้องทำซ้ำสตริง **value** |

### ค่าที่ส่งกลับ

This pointer.

## StringBuilder::Insert(int, char_t) เมธอด


แทรกอักขระเข้าไปในตำแหน่งคงที่ของตัวสร้าง.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ตำแหน่งที่จะแทรกอักขระเข้าไป |
| ch | char_t | อักขระที่จะแทรก |

### ค่าที่ส่งกลับ

This pointer.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) เมธอด


แทรกอักขระหลายตัวเข้าไปในตำแหน่งคงที่ของตัวสร้าง.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะแทรกอักขระเข้าไป |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) เพื่อแทรกส่วนจาก |
| startIndex | int | [Array](../../../system/array/) ดัชนีเริ่มต้นของส่วน |
| charCount | int | [Array](../../../system/array/) ความยาวของส่วน |

### ค่าที่ส่งกลับ

This pointer.

## StringBuilder::Insert(int, T) เมธอด


แทรกค่าเข้าไปในตำแหน่งคงที่ของตัวสร้าง.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Parameter | ประเภท. |

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ตำแหน่งที่จะแทรกอักขระเข้าไป |
| value | T | ค่าที่จะฟอร์แมตและแทรก |

### ค่าที่ส่งกลับ

This pointer.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [StringBuilder](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* Library [Aspose.Slides](../../../)