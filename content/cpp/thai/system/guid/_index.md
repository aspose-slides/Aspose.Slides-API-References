---
title: Guid
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "แสดงตัวระบุที่ไม่ซ้ำกันทั่วโลก (Globally Unique Identifier) ชนิดนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจ็กต์ของชนิดนี้."
type: docs
weight: 885
url: /th/system/guid/
---
## Guid คลาส

แสดงตัวระบุที่ไม่ซ้ำกันทั่วโลก (Globally Unique Identifier) ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจ็กต์ของประเภทนี้.

```cpp
class Guid
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | ทำการเปรียบเทียบเชิงคณิตศาสตร์ของ GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | ระบุว่า GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| int [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน |
|  [Guid](./guid/)() | สร้างอ็อบเจ็กต์ที่แสดง GUID ที่ประกอบด้วยศูนย์ทั้งหมด |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | สร้างอ็อบเจ็กต์ที่แสดง GUID ที่ระบุเป็นอาเรย์ของค่าจำนวนเต็มบิท 8 แบบไม่มีเครื่องหมาย |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | สร้างอ็อบเจ็กต์ที่แสดง GUID ที่ระบุเป็นการดูอาเรย์ของค่าจำนวนเต็มบิท 8 แบบไม่มีเครื่องหมาย |
|  [Guid](./guid/)(const [String](../string/)\&) | สร้างอ็อบเจ็กต์ที่แสดง GUID ที่ระบุเป็นสตริง |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | สร้างอินสแตนซ์ของคลาส [Guid](./) จากส่วนประกอบของ GUID ที่ระบุ |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | สร้างอินสแตนซ์ของคลาส [Guid](./) จากส่วนประกอบของ GUID ที่ระบุ |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | สร้างอินสแตนซ์ของคลาส [Guid](./) จากจำนวนเต็มบิทแบบไม่มีเครื่องหมายและไบต์ที่ระบุ |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | สร้างอินสแตนซ์ของคลาส [Guid](./) จากจำนวนเต็มบิทแบบไม่มีเครื่องหมายและไบต์ที่ระบุ |
|  [Guid](./guid/)(const [Guid](./)\&) | สร้างอ็อบเจ็กต์ที่แสดง GUID เดียวกับอ็อบเจ็กต์ที่ระบุ |
| static [Guid](./) [NewGuid](./newguid/)() | สร้าง GUID ใหม่และคืนอ็อบเจ็กต์ [Guid](./) ที่แสดง GUID นั้น |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | ระบุว่า GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุไม่เท่ากัน |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | กำหนดค่า GUID ที่แสดงโดยอ็อบเจ็กต์ [Guid](./) ที่ระบุให้กับอ็อบเจ็กต์ปัจจุบัน |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | ระบุว่า GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงการแทนสตริงของ GUID ที่ระบุให้เป็นอ็อบเจ็กต์ [Guid](./) ที่เท่ากัน |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | แปลง GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นอาเรย์ของไบต์ |
| [String](../string/) [ToString](./tostring/)() const | แปลง GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นรูปแบบสตริง |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | แปลง GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้รูปแบบสตริงที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | แปลง GUID ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้รูปแบบสตริงและวัฒนธรรมที่ระบุ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | พยายามแปลงสตริงที่ระบุให้เป็นอ็อบเจ็กต์ [Guid](./) |
|  [~Guid](./~guid/)() | ตัวทำลาย |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | แสดง GUID ที่มีค่าเป็น 0 |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)