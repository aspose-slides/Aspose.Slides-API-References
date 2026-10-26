---
title: get_Value()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าข้อความของโหนดปัจจุบัน
type: docs
weight: 79
url: /th/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() เมธอด

คืนค่าข้อความของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### ค่าที่ส่งกลับ

ค่าที่ส่งกลับขึ้นอยู่กับ XmlValidatingReader::NodeType ของโหนด.

## หมายเหตุ

ตารางต่อไปนี้แสดงประเภทโหนดที่มีค่าที่จะส่งกลับ โหนดประเภทอื่นทั้งหมดจะส่งคืน [String::Empty](../../../system/string/empty/). 

| ประเภทโหนด | ค่า |
| --- | --- |
| [Attribute](../../../system/attribute/)| ค่าของแอตทริบิวต์ |
| CDATA| เนื้อหาของส่วน CDATA |
| Comment| เนื้อหาของคอมเมนต์ |
| DocumentType| ส่วนย่อยภายใน |
| ProcessingInstruction| เนื้อหาทั้งหมด ยกเว้นเป้าหมาย |
| SignificantWhitespace| ช่องว่างระหว่างเครื่องหมายในโมเดลเนื้อหาผสม |
| [Text](../../../system.text/)| เนื้อหาของโหนดข้อความ |
| Whitespace| ช่องว่างระหว่างเครื่องหมาย |
| [XmlDeclaration](../../xmldeclaration/)| เนื้อหาของการประกาศ |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)