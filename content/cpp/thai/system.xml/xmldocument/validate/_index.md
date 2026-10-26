---
title: Validate()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตรวจสอบ XmlDocument กับสกีม่า XML Schema Definition Language (XSD) ที่มีอยู่ในรายการ XmlDocument::get_Schemas"
type: docs
weight: 573
url: /th/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) เมธอด

ตรวจสอบ [XmlDocument](../) กับสกีม่า XML [Schema](../../../system.xml.schema/) Definition Language (XSD) ที่รวมอยู่ในรายการ [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ออบเจกต์ [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) ที่รับข้อมูลเกี่ยวกับคำเตือนและข้อผิดพลาดของการตรวจสอบสกีม่า |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) เมธอด

ตรวจสอบวัตถุ [XmlNode](../../xmlnode/) ที่ระบุกับสกีม่า XML [Schema](../../../system.xml.schema/) Definition Language (XSD) ในรายการ [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ออบเจกต์ [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) ที่รับข้อมูลเกี่ยวกับคำเตือนและข้อผิดพลาดของการตรวจสอบสกีม่า |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | ออบเจกต์ [XmlNode](../../xmlnode/) ที่สร้างจาก [XmlDocument](../) เพื่อทำการตรวจสอบ |

## ดูเพิ่มเติม

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlDocument](../)
* คลาส [XmlNode](../../xmlnode/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)