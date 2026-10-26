---
title: ParseValue()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะตรวจสอบสตริงที่ระบุกับประเภทแบบง่ายที่มีในตัวหรือที่ผู้ใช้กำหนด
type: docs
weight: 53
url: /th/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

เมื่อถูกเขียนทับในคลาสที่สืบทอด จะตรวจสอบ **สตริง** ที่ระบุกับประเภทแบบง่ายที่มีในตัวหรือที่ผู้ใช้กำหนด

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| s | [String](../../../system/string/) | **สตริง** ที่จะตรวจสอบกับประเภทแบบง่าย |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) ที่จะใช้สำหรับการทำอะตอมขณะพาร์ส **สตริง** หากอ็อบเจ็กต์ [XmlSchemaDatatype](../) นี้เป็นประเภท **xs:NCName** |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่จะใช้ขณะพาร์ส **สตริง** หากอ็อบเจ็กต์ [XmlSchemaDatatype](../) นี้เป็นประเภท **xs:QName** |

### ค่าที่คืนกลับ

[Object](../../../system/object/) ที่สามารถแคสต์อย่างปลอดภัยเป็นชนิดที่คืนค่าจากการเรียก [XmlSchemaDatatype::get_ValueType](../get_valuetype/)

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNameTable](../../../system.xml/xmlnametable/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XmlSchemaDatatype](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)