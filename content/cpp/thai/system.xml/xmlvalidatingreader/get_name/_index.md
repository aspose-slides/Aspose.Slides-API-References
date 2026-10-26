---
title: get_Name()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนชื่อที่ครบถ้วนของโหนดปัจจุบัน
type: docs
weight: 14
url: /th/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() เมธอด

ส่งคืนชื่อที่ครบถ้วนของโหนดปัจจุบัน

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### ค่าที่ส่งคืน

ชื่อที่ครบถ้วนของโหนดปัจจุบัน ตัวอย่างเช่น **Name** คือ **bk:book** สำหรับองค์ประกอบ **<bk:book>**.

## หมายเหตุ

ชื่อที่ส่งคืนจะขึ้นอยู่กับ XmlValidatingReader::NodeType ของโหนด ประเภทโหนดต่อไปนี้จะส่งค่าตามที่ระบุ ทั้งประเภทโหนดอื่น ๆ จะส่งสตริงว่าง

| ประเภทโหนด | ชื่อ |
| --- | --- |
| [Attribute](../../../system/attribute/)| ชื่อของแอตทริบิวท์ |
| DocumentType| ชื่อประเภทเอกสาร |
| Element| ชื่อแท็ก |
| EntityReference| ชื่อของเอนทิตี้ที่อ้างอิง |
| ProcessingInstruction| เป้าหมายของคำสั่งประมวลผล |
| [XmlDeclaration](../../xmldeclaration/)| สตริงลิเทอรัล `xml` |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)