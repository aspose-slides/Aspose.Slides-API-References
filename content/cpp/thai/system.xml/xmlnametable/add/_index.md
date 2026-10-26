---
title: Add()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เมื่อทำการ override ในคลาสย่อย จะทำให้สตริงที่ระบุเป็นอะตอมและเพิ่มลงใน XmlNameTable.
type: docs
weight: 14
url: /th/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) เมธอด


When overridden in a derived class, ทำให้สตริงที่ระบุเป็นอะตอมและเพิ่มลงไปใน [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | อาเรย์ของอักขระที่ประกอบด้วยชื่อที่จะเพิ่ม. |
| offset | **int32_t** | ดัชนีเริ่มจากศูนย์ในอาเรย์ที่ระบุตัวอักษรตัวแรกของชื่อ. |
| length | **int32_t** | จำนวนอักขระในชื่อ. |

### ค่าที่ส่งคืน

สตริงที่ทำให้เป็นอะตอมใหม่หรือสตริงที่มีอยู่แล้วถ้ามีอยู่แล้ว หากความยาวเป็นศูนย์ จะคืนค่า [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) เมธอด


When overridden in a derived class, ทำให้สตริงที่ระบุเป็นอะตอมและเพิ่มลงไปใน [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | ชื่อที่จะเพิ่ม. |

### ค่าที่ส่งคืน

สตริงที่ทำให้เป็นอะตอมใหม่หรือสตริงที่มีอยู่แล้วถ้ามีอยู่แล้ว.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNameTable](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)