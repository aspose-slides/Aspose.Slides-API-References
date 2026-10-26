---
title: ReadElementContentAsObject()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็น Object.
type: docs
weight: 469
url: /th/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() เมธอด


อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็น [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### ค่าที่คืน

อ็อบเจกต์ที่บรรจุไว้ในกล่องของชนิดที่เหมาะสมที่สุด ค่าของ [XmlReader::get_ValueType](../get_valuetype/) กำหนดชนิดที่เหมาะสม หากเนื้อหาเป็นประเภทรายการ เมธอดนี้จะส่งคืนอาร์เรย์ของอ็อบเจกต์ที่บรรจุในกล่องของชนิดที่เหมาะสม

## XmlReader::ReadElementContentAsObject(String, String) เมธอด


ตรวจสอบว่าชื่อท้องถิ่นและ URI เนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่ จากนั้นอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็น [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบ |

### ค่าที่คืน

อ็อบเจกต์ที่บรรจุไว้ในกล่องของชนิดที่เหมาะสมที่สุด ค่าของ [XmlReader::get_ValueType](../get_valuetype/) กำหนดชนิดที่เหมาะสม หากเนื้อหาเป็นประเภทรายการ เมธอดนี้จะส่งคืนอาร์เรย์ของอ็อบเจกต์ที่บรรจุในกล่องของชนิดที่เหมาะสม

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [XmlReader](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)