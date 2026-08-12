---
title: get_Value()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าข้อความของโหนดปัจจุบัน.
type: docs
weight: 79
url: /th/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() เมธอด

คืนค่าข้อความของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### ค่าที่ส่งคืน

ค่าที่ส่งคืนขึ้นอยู่กับค่า [XmlTextReader::get_NodeType](../get_nodetype/) ของโหนด.

## หมายเหตุ

ตารางต่อไปนี้แสดงประเภทโหนดที่มีค่าที่ต้องส่งคืน โหนดประเภทอื่นทั้งหมดจะส่งคืน [String::Empty](../../../system/string/empty/). 

| ประเภทโหนด | ค่า |
| --- | --- |
| [Attribute](../../../system/attribute/)| ค่าของแอตทริบิวต์. |
| CDATA| เนื้อหาของส่วน CDATA. |
| Comment| เนื้อหาของคอมเมนต์. |
| DocumentType| ส่วนย่อยภายใน. |
| ProcessingInstruction| เนื้อหาทั้งหมด ยกเว้นเป้าหมาย. |
| SignificantWhitespace| ช่องว่างภายในขอบเขต `xml:space='preserve'`. |
| [Text](../../../system.text/)| เนื้อหาของโหนดข้อความ. |
| Whitespace| ช่องว่างระหว่างมาร์กอัป. |
| [XmlDeclaration](../../xmldeclaration/)| เนื้อหาของการประกาศ. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)