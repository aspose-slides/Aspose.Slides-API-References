---
title: ReadElementString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อ่านองค์ประกอบที่เป็นข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด XmlReader::ReadElementContentAsString แทน เพราะมันให้วิธีที่ตรงไปตรงมามากขึ้นในการจัดการการดำเนินการนี้."
type: docs
weight: 859
url: /th/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() เมธอด

อ่านองค์ประกอบที่เป็นข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) แทน เพราะมันให้วิธีที่ตรงไปตรงมามากขึ้นในการจัดการการดำเนินการนี้.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### ค่าที่คืนกลับ

ข้อความที่บรรจุในองค์ประกอบที่อ่านได้ ค่าข้อความว่างหากองค์ประกอบว่างเปล่า.

## XmlReader::ReadElementString(String) เมธอด

ตรวจสอบว่าค่า [XmlReader::get_Name](../get_name/) ขององค์ประกอบที่พบตรงกับสตริงที่กำหนดก่อนอ่านองค์ประกอบที่เป็นข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) แทน เพราะมันให้วิธีที่ตรงไปตรงมามากขึ้นในการจัดการการดำเนินการนี้.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่ต้องตรวจสอบ. |

### ค่าที่คืนกลับ

ข้อความที่บรรจุในองค์ประกอบที่อ่านได้ ค่าข้อความว่างหากองค์ประกอบว่างเปล่า.

## XmlReader::ReadElementString(String, String) เมธอด

ตรวจสอบว่าค่า [XmlReader::get_LocalName](../get_localname/) และ [XmlReader::get_NamespaceURI](../get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่กำหนดก่อนอ่านองค์ประกอบที่เป็นข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) แทน เพราะมันให้วิธีที่ตรงไปตรงมามากขึ้นในการจัดการการดำเนินการนี้.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localname | [String](../../../system/string/) | ชื่อท้องถิ่นที่ต้องตรวจสอบ. |
| ns | [String](../../../system/string/) | URI ของเนมสเปซที่ต้องตรวจสอบ. |

### ค่าที่คืนกลับ

ข้อความที่บรรจุในองค์ประกอบที่อ่านได้ ค่าข้อความว่างหากองค์ประกอบว่างเปล่า.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)