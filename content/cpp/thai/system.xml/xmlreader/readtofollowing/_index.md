---
title: ReadToFollowing()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านจนกระทั่งพบองค์ประกอบที่มีชื่อที่กำหนดตามคุณลักษณะ
type: docs
weight: 898
url: /th/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) วิธีการ

อ่านจนกระทั่งพบองค์ประกอบที่มีชื่อที่กำหนดตามคุณลักษณะ

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่กำหนดตามคุณลักษณะขององค์ประกอบ |

### ค่าที่ส่งคืน

**true** หากพบองค์ประกอบที่ตรงกัน; มิฉะนั้น **false** และ [XmlReader](../) อยู่ในสถานะไฟล์สิ้นสุด

## XmlReader::ReadToFollowing(String, String) วิธีการ

อ่านจนกระทั่งพบองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่กำหนด

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบ |

### ค่าที่ส่งคืน

**true** หากพบองค์ประกอบที่ตรงกัน; มิฉะนั้น **false** และ [XmlReader](../) อยู่ในสถานะไฟล์สิ้นสุด

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)