---
title: ValidateElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบองค์ประกอบในบริบทปัจจุบัน.
type: docs
weight: 131
url: /th/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) เมธอด


ตรวจสอบองค์ประกอบในบริบทปัจจุบัน.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นขององค์ประกอบที่ต้องการตรวจสอบ. |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซขององค์ประกอบที่ต้องการตรวจสอบ. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | วัตถุ [XmlSchemaInfo](../../xmlschemainfo/) ที่มีคุณสมบัติตั้งค่าเมื่อการตรวจสอบชื่อขององค์ประกอบสำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) เมธอด


ตรวจสอบองค์ประกอบในบริบทปัจจุบันพร้อมกับค่าแอตทริบิวต์ **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, และ **xsi:NoNamespaceSchemaLocation** ที่ระบุ.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นขององค์ประกอบที่ต้องการตรวจสอบ. |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซขององค์ประกอบที่ต้องการตรวจสอบ. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | วัตถุ [XmlSchemaInfo](../../xmlschemainfo/) ที่มีคุณสมบัติตั้งค่าเมื่อการตรวจสอบชื่อขององค์ประกอบสำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |
| xsiType | const [String](../../../system/string/)\& | ค่าแอตทริบิวต์ **xsi:Type** ขององค์ประกอบนี้ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |
| xsiNil | const [String](../../../system/string/)\& | ค่าแอตทริบิวต์ **xsi:Nil** ขององค์ประกอบนี้ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | ค่าแอตทริบิวต์ **xsi:SchemaLocation** ขององค์ประกอบนี้ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | ค่าแอตทริบิวต์ **xsi:NoNamespaceSchemaLocation** ขององค์ประกอบนี้ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)