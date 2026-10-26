---
title: CharacterRange
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงช่วงตำแหน่งอักขระในสตริง ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของประเภทนี้"
type: docs
weight: 40
url: /th/system.drawing/characterrange/
---
## CharacterRange คลาส

แสดงช่วงตำแหน่งอักขระในสตริง ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส [System::SmartPtr](../../system/smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้

```cpp
class CharacterRange
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [CharacterRange](./) ที่แสดงช่วงที่ระบุ |
|  [CharacterRange](./characterrange/)() | สร้างอินสแตนซ์ใหม่ของคลาส [CharacterRange](./) ที่แสดงช่วงว่าง |
| **int32_t** [get_First](./get_first/)() const | คืนค่าตำแหน่งของอักขระตัวแรกของช่วงที่วัตถุปัจจุบันแสดง |
| **int32_t** [get_Length](./get_length/)() const | คืนค่าจำนวนอักขระในช่วงที่วัตถุปัจจุบันแสดง |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุแสดงช่วงที่แตกต่างกันหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุแสดงช่วงเดียวกันหรือไม่ |
| void [set_First](./set_first/)(**int32_t**) | ตั้งค่าตำแหน่งของอักขระตัวแรกของช่วงที่วัตถุปัจจุบันแสดง |
| void [set_Length](./set_length/)(**int32_t**) | คืนค่าจำนวนอักขระในช่วงที่วัตถุปัจจุบันแสดง |

## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)