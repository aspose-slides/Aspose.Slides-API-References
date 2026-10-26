---
title: BitVector32
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้บิตเวกเตอร์ที่มีน้ำหนักเบาและเรียบง่ายพร้อมการเข้าถึงแบบจำนวนเต็มหรือบูลีนที่ง่ายสำหรับการจัดเก็บ 32 บิต.
type: docs
weight: 1
url: /th/system.collections.specialized/bitvector32/
---
## BitVector32 คลาส

ให้บิตเวกเตอร์ที่มีน้ำหนักเบาและเรียบง่ายพร้อมการเข้าถึงแบบจำนวนเต็มหรือ [Boolean](../../system/boolean/) ที่ง่ายต่อการใช้งานสำหรับการจัดเก็บ 32 บิต.

```cpp
class BitVector32
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BitVector32](./bitvector32/)() | สร้างอินสแตนซ์ใหม่ที่ว่างของ [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | สร้างอินสแตนซ์ใหม่ของโครงสร้าง [BitVector32](./) ด้วยข้อมูลภายในที่ระบุ. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | สร้างอินสแตนซ์ใหม่ของโครงสร้าง [BitVector32](./) ด้วยข้อมูลจากค่าที่ระบุ. |
| static **int32_t** [CreateMask](./createmask/)() | สร้างมาสก์แรกในชุด. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | สร้างมาสก์ต่อไปในชุด. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | สร้างส่วนแรกในชุด ด้วยค่ามากสุดที่ระบุ. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | สร้างส่วนต่อไปในชุด ด้วยค่ามากสุดที่ระบุ. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | กำหนดว่าควัตถุที่ระบุเป็นเหมือนกับอ็อบเจกต์ปัจจุบันหรือไม่. |
| **int32_t** [get_Data](./get_data/)() | คืนค่าข้อมูลดิบที่จัดเก็บในบิตเวกเตอร์นี้... |
| **int32_t** [GetHashCode](./gethashcode/)() const | คืนค่าฮัชโค้ดสำหรับอ็อบเจกต์ปัจจุบัน. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | รับค่าที่บ่งบอกว่าบิตทั้งหมดที่ระบุถูกตั้งค่าแล้วหรือไม่. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | รับค่าของส่วนที่ระบุ. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | ตั้งค่าที่บ่งบอกว่าบิตทั้งหมดที่ระบุถูกตั้งค่าแล้วหรือไม่. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | ตั้งค่าของส่วนที่ระบุ. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | แปลงค่าที่แสดงโดยพารามิเตอร์ค่าเป็นสตริง. |
| [String](../../system/string/) [ToString](./tostring/)() const | แปลงค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็นสตริง. |
## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Specialized](../)
* ไลบรารี [Aspose.Slides](../../)