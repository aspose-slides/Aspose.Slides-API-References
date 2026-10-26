---
title: Index
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นตัวแทนของดัชนีในคอลเลกชัน ดัชนีอาจมาจากจุดเริ่มต้นหรือจากจุดสิ้นสุด ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง อย่าใช้คลาส System::SmartPtr เพื่อจัดการวัตถุของประเภทนี้"
type: docs
weight: 1015
url: /th/system/index/
---
## คลาส Index

เป็นตัวแทนของดัชนีในคอลเลกชัน ดัชนีอาจมาจากจุดเริ่มต้นหรือจากจุดสิ้นสุด ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ห้ามใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการวัตถุของประเภทนี้.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | กำหนดว่าตัวอย่างปัจจุบันและ [Index](./) ที่ระบุแสดงตำแหน่งเดียวกันหรือไม่ |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | สร้าง [Index](./) ที่สัมพันธ์กับจุดสิ้นสุดของคอลเลกชัน |
| static constexpr [Index](./) [get_End](./get_end/)() | รับออบเจ็กต์ [Index](./) ที่แสดงจุดสิ้นสุดของคอลเลกชัน |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | รับค่าที่บ่งชี้ว่าดัชนีมาจากจุดสิ้นสุดหรือไม่ |
| static constexpr [Index](./) [get_Start](./get_start/)() | รับออบเจ็กต์ [Index](./) ที่แสดงจุดเริ่มต้นของคอลเลกชัน |
| constexpr **int32_t** [get_Value](./get_value/)() const | รับค่าดัชนี |
| **int32_t** [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดสำหรับดัชนีปัจจุบัน |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | แปลง [Index](./) ปัจจุบันเป็นการชดเชยจากจุดเริ่มต้นของคอลเลกชันที่มีความยาวที่ระบุ |
| constexpr [Index](./index/)() | สร้างตัวอย่างที่แสดงจุดเริ่มต้นของคอลเลกชัน |
| constexpr [Index](./index/)(**int32_t**) | สร้างตัวอย่างที่แสดงตำแหน่งที่ระบุจากจุดเริ่มต้นของคอลเลกชัน |
| constexpr [Index](./index/)(**int32_t**, **bool**) | สร้างตัวอย่างที่แสดงดัชนีที่ระบุ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)