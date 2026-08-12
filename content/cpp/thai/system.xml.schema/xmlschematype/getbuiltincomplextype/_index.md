---
title: GetBuiltInComplexType()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืน XmlSchemaComplexType ที่เป็นตัวแทนของประเภทซับซ้อนที่สร้างไว้ล่วงหน้าของประเภทซับซ้อนที่ระบุ
type: docs
weight: 196
url: /th/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) method

ส่งคืน [XmlSchemaComplexType](../../xmlschemacomplextype/) ที่เป็นตัวแทนของประเภทซับซ้อนที่สร้างไว้ล่วงหน้าของประเภทซับซ้อนที่ระบุ

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | หนึ่งในค่า XmlTypeCode ที่แสดงถึงประเภทซับซ้อน |

### Return Value

[XmlSchemaComplexType](../../xmlschemacomplextype/) ที่เป็นตัวแทนของประเภทซับซ้อนที่สร้างไว้ล่วงหน้า

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) method

ส่งคืน [XmlSchemaComplexType](../../xmlschemacomplextype/) ที่เป็นตัวแทนของประเภทซับซ้อนที่สร้างไว้ล่วงหน้าของประเภทซับซ้อนที่ระบุด้วยชื่อที่มีคุณสมบัติครบ

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) ของประเภทซับซ้อน |

### Return Value

[XmlSchemaComplexType](../../xmlschemacomplextype/) ที่เป็นตัวแทนของประเภทซับซ้อนที่สร้างไว้ล่วงหน้า

## See Also

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaComplexType](../../xmlschemacomplextype/)
* Class [XmlSchemaType](../)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)