---
title: XmlSchemaValidator()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส XmlSchemaValidator
type: docs
weight: 92
url: /th/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | อ็อบเจ็กต์ [XmlNameTable](../../../system.xml/xmlnametable/) ที่มีชื่อขององค์ประกอบและแอตทริบิวต์เป็นสตริงที่ทำให้อยู่ในรูปแบบอะตอม |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | อ็อบเจ็กต์ [XmlSchemaSet](../../xmlschemaset/) ที่มีสกีม XML [Schema](../../) Definition Language (XSD) ใช้สำหรับการตรวจสอบความถูกต้อง |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | อ็อบเจ็กต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้สำหรับการแก้ไขเนมสเปซที่พบระหว่างการตรวจสอบความถูกต้อง |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | ค่า XmlSchemaValidationFlags ที่ระบุตัวเลือกการตรวจสอบสกีม |

## ดูเพิ่มเติม

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNameTable](../../../system.xml/xmlnametable/)
* คลาส [XmlSchemaSet](../../xmlschemaset/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)