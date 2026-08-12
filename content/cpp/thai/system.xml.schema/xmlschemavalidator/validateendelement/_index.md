---
title: ValidateEndElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าข้อความขององค์ประกอบเป็นค่าที่ถูกต้องตามประเภทข้อมูลสำหรับองค์ประกอบที่มีเนื้อหาง่าย และตรวจสอบว่าข้อมูลขององค์ประกอบปัจจุบันสมบูรณ์สำหรับองค์ประกอบที่มีเนื้อหาซับซ้อน
type: docs
weight: 209
url: /th/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) เมธอด

ตรวจสอบว่าข้อความขององค์ประกอบเป็นค่าที่ถูกต้องตามประเภทข้อมูลสำหรับองค์ประกอบที่มีเนื้อหาง่ายและตรวจสอบว่าข้อมูลขององค์ประกอบปัจจุบันสมบูรณ์สำหรับองค์ประกอบที่มีเนื้อหาซับซ้อน

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | วัตถุ [XmlSchemaInfo](../../xmlschemainfo/) ที่คุณสมบัติมากำหนดเมื่อการตรวจสอบความถูกต้องขององค์ประกอบสำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr**. |

### ค่าที่ส่งคืน

ค่าข้อความที่แยกวิเคราะห์และระบุประเภทขององค์ประกตอน หากองค์ประกอบมีเนื้อหาง่าย

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) เมธอด

ตรวจสอบว่าข้อความขององค์ประกอบที่ระบุเป็นค่าที่ถูกต้องตามประเภทข้อมูลของมัน

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | วัตถุ [XmlSchemaInfo](../../xmlschemainfo/) ที่คุณสมบัติมากำหนดเมื่อการตรวจสอบความถูกต้องของข้อความขององค์ประกอบสำเร็จ พารามิเตอร์นี้สามารถเป็น **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | เนื้อหาข้อความที่เป็นประเภทขององค์ประกอบ. |

### ค่าที่ส่งคืน

เนื้อหาง่ายที่แยกวิเคราะห์และระบุประเภทขององค์ประกอบ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [XmlSchemaInfo](../../xmlschemainfo/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)