---
title: CompareOrdinal()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เปรียบเทียบสองสตริงโดยใช้โหมดออร์เดินัล (น้อย-เท่า-มาก).
type: docs
weight: 833
url: /th/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) method

เปรียบเทียบสองสตริงโดยใช้โหมดออร์ดินัล (น้อย-เท่า-มาก).

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องเปรียบเทียบ |
| strB | const [String](../)\& | สตริงที่สองที่ต้องเปรียบเทียบ |

### ค่าที่ส่งคืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::CompareOrdinal(const String\&, int, const String\&, int, int) method

เปรียบเทียบสองสตริงโดยใช้โหมดออร์ดินัล (น้อย-เท่า-มาก).

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องเปรียบเทียบ |
| indexA | int | ตำแหน่งเริ่มต้นของส่วนย่อยของสตริงแรก |
| strB | const [String](../)\& | สตริงที่สองที่ต้องเปรียบเทียบ |
| indexB | int | ตำแหน่งเริ่มต้นของส่วนย่อยของสตริงที่สอง |
| length | int | จำนวนอักขระที่ต้องเปรียบเทียบ |

### ค่าที่ส่งคืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## ดูเพิ่มเติม

* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)