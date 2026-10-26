---
title: get_SchemaType()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คืนอ็อบเจ็กต์ประเภทสกีม่า.
type: docs
weight: 287
url: /th/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() เมธอด


คืนอ็อบเจ็กต์ประเภทสกีม่า.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### ค่าที่ส่งคืน

XmlSchemaDatatype, XmlSchemaSimpleType, หรือ XmlSchemaComplexType ขึ้นอยู่กับว่าค่าโหนดเป็นประเภทที่สร้างขึ้นในตัวของ XML [Schema](../../../system.xml.schema/) definition language (XSD) หรือเป็น simpleType หรือ complexType ที่ผู้ใช้กำหนด; **nullptr** หากโหนดปัจจุบันไม่มีประเภทสกีม่า.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)