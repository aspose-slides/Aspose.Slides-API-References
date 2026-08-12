---
title: get_Value()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะรับค่าข้อความของโหนดปัจจุบัน
type: docs
weight: 92
url: /th/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() เมธอด


When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### ค่าที่ส่งกลับ

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.
## หมายเหตุ



The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| ค่าของแอตทริบิวต์. |
| `CDATA`| เนื้อหาของส่วน CDATA. |
| `Comment`| เนื้อหาของคอมเมนต์. |
| `DocumentType`| ส่วนย่อยภายใน. |
| `ProcessingInstruction`| เนื้อหาทั้งหมด ยกเว้นเป้าหมาย. |
| `SignificantWhitespace`| ช่องว่างระหว่างเครื่องหมายมาร์กอัปในโมเดลเนื้อหาผสม. |
| `[Text](../../../system.text/)`| เนื้อหาของโหนดข้อความ. |
| `Whitespace`| ช่องว่างระหว่างเครื่องหมายมาร์กอัป. |
| [XmlDeclaration](../../xmldeclaration/)| เนื้อหาของการประกาศ. |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)