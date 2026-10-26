---
title: get_Name()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนชื่อที่เต็มรูปแบบของโหนดปัจจุบัน.
type: docs
weight: 14
url: /th/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() เมธอด


คืนชื่อที่เต็มรูปแบบของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### ค่าที่ส่งกลับ

ชื่อที่เต็มรูปแบบของโหนดปัจจุบัน ตัวอย่างเช่น **Name** มีค่าเป็น **bk:book** สำหรับเอลิเมนต์ **<bk:book>**.

## หมายเหตุ



ชื่อที่ส่งกลับขึ้นอยู่กับค่า [XmlNodeReader::get_NodeType](../get_nodetype/) ของโหนด ประเภทโหนดต่อไปนี้จะคืนค่าตามที่ระบุ ส่วนประเภทโหนดอื่น ๆ จะคืนสตริงว่าง. 

| Node Type | ชื่อ |
| --- | --- |
| [Attribute](../../../system/attribute/)| ชื่อของแอตทริบิวต์ |
| DocumentType| ชื่อประเภทเอกสาร |
| Element| ชื่อแท็ก |
| EntityReference| ชื่อของเอนทิตี้ที่อ้างอิง |
| ProcessingInstruction| เป้าหมายของคำสั่งประมวลผล |
| [XmlDeclaration](../../xmldeclaration/)| สตริงตรง `xml` |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeReader](../)
* เนมส페ซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)