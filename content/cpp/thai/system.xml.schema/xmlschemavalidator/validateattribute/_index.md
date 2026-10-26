---
title: ValidateAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบชื่อแอตทริบิวต์, URI ของเนมสเปซ, และค่าภายในบริบทขององค์ประกอบปัจจุบัน.
type: docs
weight: 144
url: /th/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method

ตรวจสอบชื่อแอ็ตทริบิวต์, URI ของเนมสเปซ, และค่าในบริบทขององค์ประกอบปัจจุบัน

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์ที่ต้องตรวจสอบ |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซของแอตทริบิวต์ที่ต้องตรวจสอบ |
| attributeValue | const [String](../../../system/string/)\& | ค่าของแอตทริบิวต์ที่ต้องตรวจสอบ |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | อ็อบเจ็กต์ [XmlSchemaInfo](../../xmlschemainfo/) ที่คุณสมบัติของมันจะถูกตั้งค่าเมื่อการตรวจสอบแอตทริบิวต์สำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้ |

### ค่าที่ส่งกลับ

ค่าของแอตทริบิวต์ที่ตรวจสอบแล้ว

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method

ตรวจสอบชื่อแอ็ตทริบิวต์, URI ของเนมสเปซ, และค่าในบริบทขององค์ประกอบปัจจุบัน

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์ที่ต้องตรวจสอบ |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซของแอตทริบิวต์ที่ต้องตรวจสอบ |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | คอลแบ็ก XmlValueGetter ที่ใช้ส่งค่าของแอตทริบิวต์ในรูปแบบที่เข้ากันได้กับประเภท XSD (XML [Schema](../../) Definition Language) ของแอตทริบิวต์ |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | อ็อบเจ็กต์ [XmlSchemaInfo](../../xmlschemainfo/) ที่คุณสมบัติของมันจะถูกตั้งค่าเมื่อการตรวจสอบแอตทริบิวต์สำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้ |

### ค่าที่ส่งกลับ

ค่าของแอตทริบิวต์ที่ตรวจสอบแล้ว

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)