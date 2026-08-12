---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสกีมาภาษา XML Schema definition (XSD) ที่ระบุ URL ไปยัง XmlSchemaSet.
type: docs
weight: 157
url: /th/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) เมธอด

เพิ่มสกีมาภาษา XML [Schema](../../) (XSD) ที่ระบุ URL ไปยัง [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | ค่า **targetNamespace** ของสกีมา, หรือ **nullptr** เพื่อใช้ **targetNamespace** ที่ระบุในสกีมา. |
| schemaUri | const [String](../../../system/string/)\& | URL ที่ระบุสกีมาที่จะโหลด. |

### Return Value

อ็อบเจ็กต์ [XmlSchema](../../xmlschema/) หากสกีมาถูกต้อง หากสกีมาไม่ถูกต้องและมี ValidationEventHandler ระบุไว้ จะคืนค่า **nullptr** และเกิดเหตุการณ์การตรวจสอบที่เหมาะสม มิฉะนั้นจะขว้าง XmlSchemaException.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) เมธอด

เพิ่มสกีมาภาษา XML [Schema](../../) (XSD) ที่อยู่ใน [XmlReader](../../../system.xml/xmlreader/) ไปยัง [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | ค่า **targetNamespace** ของสกีมา, หรือ **nullptr** เพื่อใช้ **targetNamespace** ที่ระบุในสกีมา. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/). |

### Return Value

อ็อบเจ็กต์ [XmlSchema](../../xmlschema/) หากสกีมาถูกต้อง หากสกีมาไม่ถูกต้องและมี ValidationEventHandler ระบุไว้ จะคืนค่า **nullptr** และเกิดเหตุการณ์การตรวจสอบที่เหมาะสม มิฉะนั้นจะขว้าง XmlSchemaException.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) เมธอด

เพิ่มสกีมาทั้งหมดของภาษา XML [Schema](../../) (XSD) ที่อยู่ใน [XmlSchemaSet](../) ให้กับ [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | อ็อบเจ็กต์ [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) เมธอด

เพิ่ม [XmlSchema](../../xmlschema/) ที่กำหนดให้กับ [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | อ็อบเจ็กต์ [XmlSchema](../../xmlschema/) ที่จะเพิ่มไปยัง [XmlSchemaSet](../). |

### Return Value

อ็อบเจ็กต์ [XmlSchema](../../xmlschema/) หากสกีมาถูกต้อง หากสกีมาไม่ถูกต้องและมี ValidationEventHandler ระบุไว้ จะคืนค่า **nullptr** และเกิดเหตุการณ์การตรวจสอบที่เหมาะสม มิฉะนั้นจะขว้าง XmlSchemaException.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)