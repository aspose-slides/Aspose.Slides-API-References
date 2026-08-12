---
title: Version
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงหมายเลขเวอร์ชัน ชนิดนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจ็กต์ของชนิดนี้."
type: docs
weight: 1470
url: /th/system/version/
---
## Version คลาส

Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Version
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | เปรียบเทียบเวอร์ชันที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | กำหนดว่าหมายเลขเวอร์ชันที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่. |
| int [get_Build](./get_build/)() const | ส่งคืนหมายเลขการสร้าง. |
| int [get_Major](./get_major/)() const | ส่งคืนเวอร์ชันหลัก. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | ส่งคืนค่าบิตสูง 16 บิตของหมายเลขการแก้ไข. |
| int [get_Minor](./get_minor/)() const | ส่งคืนเวอร์ชันย่อย. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | ส่งคืนค่าบิตต่ำ 16 บิตของหมายเลขการแก้ไข. |
| int [get_Revision](./get_revision/)() const | ส่งคืนหมายเลขการแก้ไข. |
| int [GetHashCode](./gethashcode/)() const | ส่งคืนรหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงการแสดงผลเป็นสตริงของหมายเลขเวอร์ชันเป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | ส่งคืนการแสดงผลเป็นสตริงของหมายเลขเวอร์ชันที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| [String](../string/) [ToString](./tostring/)(int) const | ส่งคืนการแสดงผลเป็นสตริงของจำนวนส่วนที่ระบุของหมายเลขเวอร์ชันที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| [Version](./version/)(int, int, int, int) | สร้างอินสแตนซ์ที่แสดงค่าหลัก, ค่าย่อย, ค่าการสร้างและค่าการแก้ไขที่ระบุ. |
| [Version](./version/)(int, int, int) | สร้างอินสแตนซ์ที่แสดงค่าหลัก, ค่าย่อยและค่าการสร้างที่ระบุ. |
| [Version](./version/)(int, int) | สร้างอินสแตนซ์ที่แสดงค่าหลักและค่าที่ระบุ. |
| [Version](./version/)(const [String](../string/)\&) | สร้างอินสแตนซ์ที่แสดงหมายเลขเวอร์ชันที่แสดงเป็นสตริง. |
| [Version](./version/)() | สร้างอินสแตนซ์ที่แสดงหมายเลขเวอร์ชัน 0.0.-1.-1. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)