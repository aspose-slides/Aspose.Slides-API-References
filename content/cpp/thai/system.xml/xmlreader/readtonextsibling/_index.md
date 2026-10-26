---
title: ReadToNextSibling()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เลื่อนตำแหน่ง XmlReader ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อแบบเต็มที่ระบุ
type: docs
weight: 924
url: /th/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) เมธอด

เลื่อนตำแหน่ง [XmlReader](../) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อแบบเต็มที่ระบุ

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อแบบเต็มขององค์ประกอบพี่น้องที่คุณต้องการย้ายไป |

### ค่าที่ส่งกลับ

**true** หากพบองค์ประกอบพี่น้องที่ตรงกัน; มิฉะนั้น **false**. หากไม่พบองค์ประกอบพี่น้องที่ตรงกัน, [XmlReader](../) จะอยู่บนแท็กปิด (ค่า [XmlReader::get_NodeType](../get_nodetype/) เป็น [XmlNodeType::EndElement](../../xmlnodetype/)) ขององค์ประกอบแม่

## XmlReader::ReadToNextSibling(String, String) เมธอด

เลื่อนตำแหน่ง [XmlReader](../) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบพี่น้องที่คุณต้องการย้ายไป |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบพี่น้องที่คุณต้องการย้ายไป |

### ค่าที่ส่งกลับ

**true** หากพบองค์ประกอบพี่น้องที่ตรงกัน; มิฉะนั้น **false**. หากไม่พบองค์ประกอบพี่น้องที่ตรงกัน, [XmlReader](../) จะอยู่บนแท็กปิด (ค่า [XmlReader::get_NodeType](../get_nodetype/) เป็น [XmlNodeType::EndElement](../../xmlnodetype/)) ขององค์ประกอบแม่

## ดูเพิ่ม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)