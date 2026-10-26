---
title: Contains()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุว่า XML Schema definition language (XSD) schema ที่มี URI ของ target namespace ที่ระบุอยู่ใน XmlSchemaSet หรือไม่.
type: docs
weight: 196
url: /th/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) เมธอด

ระบุว่า XML [Schema](../../) definition language (XSD) schema ที่มี URI ของ target namespace ที่ระบุอยู่ใน [XmlSchemaSet](../) หรือไม่.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | คุณสมบัติ **targetNamespace** ของสกีม่า. |

### ค่าที่ส่งคืน

**true** หากสกีม่า ที่มี URI ของ target namespace ที่ระบุอยู่ใน [XmlSchemaSet](../); หากไม่เป็นเช่นนั้น ให้เป็น **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) เมธอด

ระบุว่าออบเจ็กต์ [XmlSchema](../../xmlschema/) ของ XML [Schema](../../) definition language (XSD) ที่ระบุอยู่ใน [XmlSchemaSet](../) หรือไม่.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | อ็อบเจ็กต์ [XmlSchema](../../xmlschema/). |

### ค่าที่ส่งคืน

**true** หากอ็อบเจ็กต์ [XmlSchema](../../xmlschema/) อยู่ใน [XmlSchemaSet](../); หากไม่เป็นเช่นนั้น ให้เป็น **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSchemaSet](../)
* คลาส [XmlSchema](../../xmlschema/)
* เนมสเปซ [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)