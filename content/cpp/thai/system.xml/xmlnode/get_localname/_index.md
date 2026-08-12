---
title: get_LocalName()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งกลับชื่อท้องถิ่นของโหนดเมื่อมีการเขียนทับในคลาสที่สืบทอด
type: docs
weight: 209
url: /th/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() method


ส่งกลับชื่อท้องถิ่นของโหนดเมื่อมีการเขียนทับในคลาสที่สืบทอด

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### ค่าที่ส่งกลับ

ชื่อของโหนดที่ถอดส่วนเติมหน้าทิ้ง ตัวอย่างเช่น **LocalName** เป็น **book** สำหรับองค์ประกอบ **<bk:book>**.

## หมายเหตุ



ชื่อที่ส่งกลับขึ้นอยู่กับ [XmlNode::get_NodeType](../get_nodetype/) ของโหนด:

| ประเภท | ชื่อ |
| --- | --- |
| [Attribute](../../../system/attribute/)| ชื่อท้องถิ่นของแอตทริบิวต์ |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | ชื่อประเภทเอกสาร |
| Element | ชื่อท้องถิ่นขององค์ประกอบ |
| Entity | ชื่อของเอนทิตี้ |
| EntityReference | ชื่อของเอนทิตี้ที่อ้างอิง |
| Notation | ชื่อของโนเทชัน |
| ProcessingInstruction | เป้าหมายของคำสั่งประมวลผล |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNode](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)