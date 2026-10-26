---
title: Schemas()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ส่งคืนคอลเลกชันของสคีม่า XML Schema definition language (XSD) ทั้งหมดใน XmlSchemaSet.
type: docs
weight: 248
url: /th/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() เมธอด

ส่งคืนคอลเลกชันของสคีม่า XML [Schema](../../) definition language (XSD) ทั้งหมดใน [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### ค่าที่ส่งคืน

ออบเจ็กต์ IList ที่ประกอบด้วยสคีม่าทั้งหมดที่ได้เพิ่มเข้าไปใน [XmlSchemaSet](../) หากไม่มีสคีม่าใดถูกเพิ่มเข้าไปใน [XmlSchemaSet](../) จะส่งคืนคอลเลกชันที่ว่างเปล่า.

## XmlSchemaSet::Schemas(String) เมธอด

ส่งคืนคอลเลกชันของสคีม่า XML [Schema](../../) definition language (XSD) ทั้งหมดใน [XmlSchemaSet](../) ที่เป็นของเนมสเปซที่กำหนด

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | คุณสมบัติสกีม่า **targetNamespace** |

### ค่าที่ส่งคืน

ออบเจ็กต์ IList ที่ประกอบด้วยสคีม่าทั้งหมดที่ได้เพิ่มเข้าไปใน [XmlSchemaSet](../) ที่เป็นของเนมสเปซที่ระบุ หากไม่มีสคีม่าใดถูกเพิ่มเข้าไปใน [XmlSchemaSet](../) จะส่งคืนคอลเลกชันที่ว่างเปล่า.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IList](../../../system.collections.generic/ilist/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [XmlSchemaSet](../)
* คลาส [List](../../../system.collections.generic/list/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)