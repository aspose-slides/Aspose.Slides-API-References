---
title: get_ParentNode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนพาเรนท์ของโหนดนี้ (สำหรับโหนดที่สามารถมีพาเรนท์).
type: docs
weight: 53
url: /th/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() เมธอด

ส่งคืนโหนดพาเรนท์ของโหนดนี้ (สำหรับโหนดที่สามารถมีพาเรนท์)

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### ค่าที่ส่งคืน

[XmlNode](../) ที่เป็นพาเรนท์ของโหนดปัจจุบัน

## หมายเหตุ

ถ้าโหนดถูกสร้างขึ้นใหม่และยังไม่ได้ถูกเพิ่มลงในต้นไม้, หรือถ้ามันถูกลบออกจากต้นไม้, พาเรนท์จะเป็น **nullptr**. สำหรับโหนดอื่น ๆ, ค่าที่ส่งคืนขึ้นอยู่กับ [XmlNode::get_NodeType](../get_nodetype/) ของโหนด. ตารางต่อไปนี้อธิบายค่าที่อาจส่งคืนสำหรับเมธอด **get_NodeType**.

| NodeType | ค่าที่ส่งคืนของ ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | ส่งคืน `nullptr`; โหนดเหล่านี้ไม่มีพาเรนท์ |
| CDATA | ส่งคืน element หรือ entity reference ที่บรรจุส่วน CDATA |
| Comment | ส่งคืน element, entity reference, document type หรือ document ที่บรรจุ Comment |
| DocumentType | ส่งคืนโหนด Document |
| Element | ส่งคืนโหนดพาเรนท์ของ element. หาก element เป็นโหนดรากในต้นไม้, พาเรนท์จะเป็นโหนด Document |
| EntityReference | ส่งคืน element, attribute หรือ entity reference ที่บรรจุ EntityReference |
| ProcessingInstruction | ส่งคืน document, element, document type หรือ entity reference ที่บรรจุ ProcessingInstruction |
| [Text](../../../system.text/) | ส่งคืน element พาเรนท์, attribute หรือ entity reference ที่บรรจุ text node |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)