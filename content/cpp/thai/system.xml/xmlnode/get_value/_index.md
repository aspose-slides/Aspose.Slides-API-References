---
title: get_Value()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนค่ของโหนด.
type: docs
weight: 14
url: /th/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() เมธอด

ส่งคืนค่าของโหนด.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### ค่าที่ส่งกลับ

ค่าที่ส่งกลับขึ้นอยู่กับ [XmlNode::get_NodeType](../get_nodetype/) ของโหนด: 

| ประเภท | ค่า |
| --- | --- |
| [Attribute](../../../system/attribute/)| ค่าของแอตทริบิวต์. |
| CDATASection | เนื้อหาของ CDATA Section. |
| Comment | เนื้อหาของคอมเมนต์. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. คุณสามารถใช้ XmlElement::InnerText หรือค่า [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) เพื่อเข้าถึงค่าของโหนด element. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | เนื้อหาทั้งหมดยกเว้นเป้าหมาย. |
| [Text](../../../system.text/)| เนื้อหาของโหนดข้อความ. |
| SignificantWhitespace | อักขระช่องว่าง. ช่องว่างอาจประกอบด้วยอักขระช่องว่างหนึ่งหรือหลายตัว, carriage returns, line feeds, หรือ tabs. |
| Whitespace | อักขระช่องว่าง. ช่องว่างอาจประกอบด้วยอักขระช่องว่างหนึ่งหรือหลายตัว, carriage returns, line feeds, หรือ tabs. |
| [XmlDeclaration](../../xmldeclaration/)| เนื้อหาของการประกาศ (คือ ทุกอย่างระหว่าง `<?xml and ?>`). |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNode](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)