---
title: get_Value()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนค่าข้อความของโหนดปัจจุบัน.
type: docs
weight: 79
url: /th/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() วิธีการ

ส่งคืนค่าข้อความของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### ค่าที่ส่งคืน

ค่าที่ส่งคืนขึ้นอยู่กับ [XmlNodeReader::get_NodeType](../get_nodetype/) ของโหนด.

## หมายเหตุ

ตารางต่อไปนี้แสดงประเภทโหนดที่มีค่าให้ส่งคืน โหนดประเภทอื่นทั้งหมดจะส่งคืน [String::Empty](../../../system/string/empty/). 

| ประเภทโหนด | ค่า |
| --- | --- |
| [Attribute](../../../system/attribute/)| ค่าของแอตทริบิวต์. |
| CDATA| เนื้อหาของส่วน CDATA. |
| Comment| เนื้อหาของคอมเมนต์. |
| DocumentType| ชุดย่อยภายใน. |
| ProcessingInstruction| เนื้อหาทั้งหมด ยกเว้นเป้าหมาย. |
| SignificantWhitespace| ช่องว่างระหว่างมาร์คอัปในโมเดลเนื้อหาผสม. |
| [Text](../../../system.text/)| เนื้อหาของโหนดข้อความ. |
| Whitespace| ช่องว่างระหว่างมาร์คอัป. |
| [XmlDeclaration](../../xmldeclaration/)| เนื้อหาของการประกาศ. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)