---
title: get_Name()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อถูก Override ในคลาสที่สืบทอด จะรับชื่อแบบ qualified ของโหนดปัจจุบัน
type: docs
weight: 27
url: /th/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() เมธอด


เมื่อถูก Override ในคลาสที่สืบทอด, จะรับชื่อแบบ qualified ของโหนดปัจจุบัน

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### ค่าที่ส่งคืน

ชื่อแบบ qualified ของโหนดปัจจุบัน ตัวอย่างเช่น **Name** มีค่าเป็น **bk:book** สำหรับ element **<bk:book>**  
## หมายเหตุ



ชื่อที่ส่งคืนขึ้นอยู่กับค่า [XmlReader::get_NodeType](../get_nodetype/) ของโหนด ประเภทโหนดต่อไปนี้จะส่งค่าตามที่ระบุ โหนดประเภทอื่นทั้งหมดจะส่งสตริงว่าง

| ประเภทโหนด | ชื่อ |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| ชื่อของแอตทริบิวต์ |
| `DocumentType`| ชื่อของประเภทเอกสาร |
| `Element`| ชื่อแท็ก |
| `EntityReference`| ชื่อของเอนทิตีที่อ้างอิง |
| `ProcessingInstruction`| เป้าหมายของคำสั่งการประมวลผล |
| [XmlDeclaration](../../xmldeclaration/)| สตริงลิเทอรัล `xml` |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)