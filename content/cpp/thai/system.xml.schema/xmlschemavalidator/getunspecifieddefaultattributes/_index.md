---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตรวจสอบข้อจำกัดเอกลักษณ์บนแอตทริบิวต์เริ่มต้นและเติมข้อมูลให้กับ List ที่ระบุด้วยอ็อบเจ็กต์ XmlSchemaAttribute สำหรับแอตทริบิวต์ที่มีค่าดีฟอลต์ซึ่งยังไม่ได้รับการตรวจสอบก่อนหน้านี้โดยใช้เมธอด XmlSchemaValidator::ValidateAttribute ในบริบทขององค์ประกอบ."
type: docs
weight: 157
url: /th/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) เมธอด

ตรวจสอบความถูกต้องของข้อจำกัดเอกลักษณ์บนแอตทริบิวต์เริ่มต้นและเติมข้อมูลให้กับ List ที่ระบุด้วยออบเจกต์ [XmlSchemaAttribute](../../xmlschemaattribute/) สำหรับแอตทริบิวต์ใด ๆ ที่มีค่าตั้งต้นซึ่งยังไม่ได้รับการตรวจสอบมาก่อนโดยใช้เมธอด [XmlSchemaValidator::ValidateAttribute](../validateattribute/) ในบริบทขององค์ประกอบ

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | List ที่จะเติมข้อมูลด้วยออบเจกต์ [XmlSchemaAttribute](../../xmlschemaattribute/) สำหรับแอตทริบิวต์ใด ๆ ที่ยังไม่เคยพบระหว่างการตรวจสอบในบริบทขององค์ประกอบ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [List](../../../system.collections.generic/list/)
* คลาส [Object](../../../system/object/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)