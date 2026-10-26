---
title: ReadStartElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนไปยังโหนดถัดไป.
type: docs
weight: 846
url: /th/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() เมธอด

ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนไปยังโหนดถัดไป

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) เมธอด

ตรวจสอบว่าโหนดเนื้อหาในปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_Name](../get_name/) ที่ระบุและเลื่อนไปยังโหนดถัดไป

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่สมบูรณ์ขององค์ประกอบ |

## XmlReader::ReadStartElement(String, String) เมธอด

ตรวจสอบว่าโหนดเนื้อหาในปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_LocalName](../get_localname/) และ [XmlReader::get_NamespaceURI](../get_namespaceuri/) ที่ระบุและเลื่อนไปยังโหนดถัดไป

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localname | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบ |
| ns | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบ |

## ดูเพิ่มเติม

* คลาส [XmlReader](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)