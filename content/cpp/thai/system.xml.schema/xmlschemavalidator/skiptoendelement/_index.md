---
title: SkipToEndElement()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ข้ามการตรวจสอบความถูกต้องของเนื้อหาอิลิเมนต์ปัจจุบันและเตรียมอ็อบเจ็กต์ XmlSchemaValidator เพื่อทำการตรวจสอบเนื้อหาในบริบทของอิลิเมนต์แม่
type: docs
weight: 222
url: /th/system.xml.schema/xmlschemavalidator/skiptoendelement/
---
## XmlSchemaValidator::SkipToEndElement(const SharedPtr\<XmlSchemaInfo\>\&) เมธอด

Skips validation of the current element content and prepares the [XmlSchemaValidator](../) object to validate content in the parent element's context.

```cpp
void System::Xml::Schema::XmlSchemaValidator::SkipToEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | อ็อบเจ็กต์ [XmlSchemaInfo](../../xmlschemainfo/) ที่มีคุณสมบัติตั้งค่าไว้หากเนื้อหาองค์ประกอบปัจจุบันถูกข้ามอย่างสำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr** ได้ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchemaInfo](../../xmlschemainfo/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)