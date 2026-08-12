---
title: ReadToDescendant()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เลื่อนตำแหน่ง XmlReader ไปยังองค์ประกอบลูกต่อไปที่มีชื่อที่ระบุแบบมีคุณสมบัติ
type: docs
weight: 911
url: /th/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) เมธอด


เลื่อนตำแหน่ง [XmlReader](../) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อที่ระบุแบบมีคุณสมบัติ

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่ระบุแบบมีคุณสมบัติขององค์ประกอบที่คุณต้องการย้ายไป |

### ค่าที่ส่งคืน

**true** หากพบองค์ประกอบลูกที่ตรงกัน; มิฉะนั้น **false** หากไม่พบองค์ประกอบลูกที่ตรงกัน, [XmlReader](../) จะอยู่บนแท็กปิด (ค่าของ [XmlReader::get_NodeType](../get_nodetype/) คือ [XmlNodeType::EndElement](../../xmlnodetype/)) ขององค์ประกอบนั้น หาก [XmlReader](../) ไม่ได้อยู่บนองค์ประกอบเมื่อเรียก [XmlReader::ReadToDescendant(String)](./), เมธอดนี้จะคืนค่า **false** และตำแหน่งของ [XmlReader](../) จะไม่เปลี่ยนแปลง

## XmlReader::ReadToDescendant(String, String) เมธอด


เลื่อนตำแหน่ง [XmlReader](../) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบที่คุณต้องการย้ายไป |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบที่คุณต้องการย้ายไป |

### ค่าที่ส่งคืน

**true** หากพบองค์ประกอบลูกที่ตรงกัน; มิฉะนั้น **false** หากไม่พบองค์ประกอบลูกที่ตรงกัน, [XmlReader](../) จะอยู่บนแท็กปิด (ค่าของ [XmlReader::get_NodeType](../get_nodetype/) คือ [XmlNodeType::EndElement](../../xmlnodetype/)) ขององค์ประกอบนั้น หาก [XmlReader](../) ไม่ได้อยู่บนองค์ประกอบเมื่อเรียก [XmlReader::ReadToDescendant(String,String)](./), เมธอดนี้จะคืนค่า **false** และตำแหน่งของ [XmlReader](../) จะไม่เปลี่ยนแปลง

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)