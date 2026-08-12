---
title: IndexOf()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides for C++
description: การค้นหาสตริงย่อยแบบต่อหน้า.
type: docs
weight: 625
url: /th/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method

การค้นหาสตริงย่อยแบบต่อหน้า.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืนกลับ

[Index](../../index/) ของสตริงย่อยที่พบเป็นครั้งแรกหรือ -1 หากไม่พบ. สำหรับสตริงการค้นหาว่างเปล่า จะคืนค่า 0 เสมอ.

## String::IndexOf(char_t, int) const method

การค้นหาตัวอักษรแบบต่อหน้า.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ตัวอักษรที่ต้องการค้นหา. |
| startIndex | int | [Index](../../index/) เพื่อเริ่มการค้นหาที่. |

### ค่าที่คืนกลับ

[Index](../../index/) ของตำแหน่งตัวอักษรแรกตั้งแต่ startIndex หรือ -1 หากไม่พบ.

## String::IndexOf(char_t, int, int) const method

การค้นหาตัวอักษรแบบต่อหน้าในสตริงย่อย.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ตัวอักษรที่ต้องการค้นหา. |
| startIndex | int | [Index](../../index/) เพื่อเริ่มการค้นหาที่. |
| count | int | จำนวนอักขระสำหรับการค้นหา. |

### ค่าที่คืนกลับ

[Index](../../index/) ของตำแหน่งตัวอักษรแรกตั้งแต่ startIndex หรือ -1 หากไม่พบ.

## String::IndexOf(const String\&, int) const method

การค้นหาสตริงย่อยแบบต่อหน้า.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับเพื่อเริ่มการค้นหาผ่าน. |

### ค่าที่คืนกลับ

[Index](../../index/) ของสตริงย่อยที่พบเป็นครั้งแรกหรือ -1 หากไม่พบ. สำหรับสตริงการค้นหาว่างเปล่า จะคืนค่า startIndex เสมอ.

## String::IndexOf(const String\&, int, System::StringComparison) const method

การค้นหาสตริงย่อยแบบต่อหน้า.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับเพื่อเริ่มการค้นหาผ่าน. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืนกลับ

[Index](../../index/) ของสตริงย่อยที่พบเป็นครั้งแรกหรือ -1 หากไม่พบ. สำหรับสตริงการค้นหาว่างเปล่า จะคืนค่า startIndex เสมอ.

## String::IndexOf(const String\&, int, int, System::StringComparison) const method

การค้นหาสตริงย่อยแบบต่อหน้า.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับเพื่อเริ่มการค้นหาผ่าน. |
| count | int | จำนวนอักขระสำหรับการค้นหา. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืนกลับ

[Index](../../index/) ของสตริงย่อยที่พบเป็นครั้งแรกหรือ -1 หากไม่พบ. สำหรับสตริงการค้นหาว่างเปล่า จะคืนค่า startIndex เสมอ.

## String::IndexOf(const String\&, int, int) const method

การค้นหาสตริงย่อยแบบต่อหน้า.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับเพื่อเริ่มการค้นหาผ่าน. |
| count | int | จำนวนอักขระสำหรับการค้นหา. |

### ค่าที่คืนกลับ

[Index](../../index/) ของสตริงย่อยที่พบเป็นครั้งแรกหรือ -1 หากไม่พบ. สำหรับสตริงการค้นหาว่างเปล่า จะคืนค่า startIndex เสมอ.

## ดูเพิ่มเติม

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)