---
title: get_Name()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าชื่อเต็มของโหนดเมื่อถูกเขียนทับในคลาสที่สืบทอด
type: docs
weight: 1
url: /th/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() เมธอด


คืนค่า ชื่อที่มีคุณลักษณะเต็มของโหนดเมื่อถูกเขียนทับในคลาสที่สืบทอด

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### ค่าที่คืน

ชื่อที่มีคุณลักษณะเต็มของโหนด
## หมายเหตุ



ชื่อที่คืนขึ้นอยู่กับ [XmlNode::get_NodeType](../get_nodetype/) ของโหนด: 

| ประเภท | ชื่อ |
| --- | --- |
| [Attribute](../../../system/attribute/)| ชื่อที่มีคุณลักษณะเต็มของแอตทริบิวต์ |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | ชื่อประเภทของเอกสาร |
| Element | ชื่อที่มีคุณลักษณะเต็มของเอลีเมนต์ |
| Entity | ชื่อของเอนทิตี |
| EntityReference | ชื่อของเอนทิตีที่อ้างอิง |
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