---
title: get_Name()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ส่งคืนชื่อที่มีคุณสมบัติเต็มของโหนดปัจจุบัน.
type: docs
weight: 14
url: /th/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() เมธอด


ส่งคืนชื่อที่มีคุณสมบัติเต็มของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### ค่าที่ส่งกลับ

ชื่อที่มีคุณสมบัติเต็มของโหนดปัจจุบัน ตัวอย่างเช่น **Name** มีค่าเป็น **bk:book** สำหรับองค์ประกอบ **<bk:book>**.

## หมายเหตุ



ชื่อที่ส่งคืนขึ้นอยู่กับค่า [XmlTextReader::get_NodeType](../get_nodetype/) ของโหนด ชนิดโหนดต่อไปนี้จะคืนค่าที่ระบุไว้ ชนิดโหนดอื่นๆ จะคืนสตริงว่าง. 

| ประเภทโหนด | ชื่อ |
| --- | --- |
| [Attribute](../../../system/attribute/)| ชื่อของแอตทริบิวต์. |
| DocumentType| ชื่อประเภทเอกสาร. |
| Element| ชื่อแท็ก. |
| EntityReference| ชื่อของเอนทิตีที่อ้างอิง. |
| ProcessingInstruction| เป้าหมายของคำสั่งประมวลผล. |
| [XmlDeclaration](../../xmldeclaration/)| สตริงลิเทอรัล `xml`. |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)