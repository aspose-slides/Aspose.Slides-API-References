---
title: Range
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงช่วงที่มีดัชนีเริ่มต้นและดัชนีสิ้นสุด. ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิง. ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการออบเจ็กท์ของประเภทนี้."
type: docs
weight: 1197
url: /th/system/range/
---
## คลาส Range

Represents a range with a start and end index. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## วิธีการ

| Method | Description |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | สร้างช่วงที่เริ่มจากจุดเริ่มต้นของคอลเลกชันและสิ้นสุดที่ดัชนีสุดท้ายที่ระบุ |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | กำหนดว่าช่วงปัจจุบันเท่ากับช่วงที่ระบุหรือไม่ |
| static constexpr [Range](./) [get_All](./get_all/)() | คืนค่า [Range](./) ที่แสดงถึงคอลเลกชันทั้งหมด |
| const [Index](../index/)\& [get_End](./get_end/)() const | รับค่า End index |
| const [Index](../index/)\& [get_Start](./get_start/)() const | รับค่า Start index |
| **int32_t** [GetHashCode](./gethashcode/)() const | คืนค่า hash code สำหรับช่วงปัจจุบัน |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | คำนวณออฟเซ็ตเริ่มต้นโดยอิงศูนย์และความยาวสำหรับความยาวคอลเลกชันที่ระบุ |
| constexpr [Range](./range/)() | สร้างช่วงที่ว่างเปล่า |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | สร้าง [Range](./) จากดัชนีเริ่มต้นและดัชนีสิ้นสุดที่ระบุ |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | สร้างช่วงที่เริ่มจากดัชนีเริ่มต้นที่ระบุและต่อถึงจุดสิ้นสุดของคอลเลกชัน |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)