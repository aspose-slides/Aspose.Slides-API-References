---
title: LastIndexOf()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: การค้นหาสตริงย่อยแบบถอยหลัง.
type: docs
weight: 651
url: /th/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const วิธีการ

การค้นหาแบบถอยหลังของสตริงย่อย.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับที่เริ่มการค้นหา. |

### ค่าที่คืน

[Index](../../index/) ของสตริงย่อยที่พบล่าสุดหรือ -1 หากไม่พบ สำหรับสตริงการค้นหาเป็นค่าว่าง จะคืนความยาวของสตริงเสมอ.

## String::LastIndexOf(const String\&, System::StringComparison) const วิธีการ

การค้นหาแบบถอยหลังของสตริงย่อย.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืน

[Index](../../index/) ของสตริงย่อยที่พบล่าสุดหรือ -1 หากไม่พบ สำหรับสตริงการค้นหาเป็นค่าว่าง จะคืนความยาวของสตริงเสมอ.

## String::LastIndexOf(const String\&, int, System::StringComparison) const วิธีการ

การค้นหาแบบถอยหลังของสตริงย่อย.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับที่เริ่มการค้นหา. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืน

[Index](../../index/) ของสตริงย่อยที่พบล่าสุดหรือ -1 หากไม่พบ สำหรับสตริงการค้นหาเป็นค่าว่าง จะคืนความยาวของสตริงเสมอ.

## String::LastIndexOf(const String\&, int, int, StringComparison) const วิธีการ

การค้นหาแบบถอยหลังของสตริงย่อย.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงย่อยที่ต้องการค้นหา. |
| startIndex | int | ตำแหน่งในสตริงต้นฉบับที่เริ่มการค้นหา. |
| count | int | จำนวนอักขระที่ต้องการค้นหา. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืน

[Index](../../index/) ของสตริงย่อยที่พบล่าสุดหรือ -1 หากไม่พบ สำหรับสตริงการค้นหาเป็นค่าว่าง จะคืนค่า startIndex+count เสมอ.

## String::LastIndexOf(char_t) const วิธีการ

การค้นหาแบบถอยหลังของอักขระ.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char_t | อักขระที่ต้องการค้นหา. |

### ค่าที่คืน

[Index](../../index/) ของตำแหน่งอักขระสุดท้ายหรือ -1 หากไม่พบ.

## String::LastIndexOf(char_t, int32_t) const วิธีการ

การค้นหาแบบถอยหลังของอักขระ.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char_t | อักขระที่ต้องการค้นหา. |
| startIndex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาที่. |

### ค่าที่คืน

[Index](../../index/) ของตำแหน่งอักขระสุดท้ายตั้งแต่ startIndex หรือ -1 หากไม่พบ.

## String::LastIndexOf(char_t, int32_t, int32_t) const วิธีการ

การค้นหาแบบถอยหลังของอักขระ.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char_t | อักขระที่ต้องการค้นหา. |
| startIndex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาที่. |
| count | **int32_t** | จำนวนอักขระที่ต้องการค้นหา |

### ค่าที่คืน

[Index](../../index/) ของตำแหน่งอักขระสุดท้ายตั้งแต่ startIndex หรือ -1 หากไม่พบ.

## ดูเพิ่มเติม

* อีนัม [StringComparison](../../stringcomparison/)
* คลาส [String](../)
* เนมส페ซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)