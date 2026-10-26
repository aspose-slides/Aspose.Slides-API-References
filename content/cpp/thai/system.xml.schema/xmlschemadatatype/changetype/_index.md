---
title: ChangeType()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แปลงค่าที่ระบุซึ่งประเภทเป็นหนึ่งในการแสดงผลที่ถูกต้องของประเภทสคีม่า XML ที่แสดงโดย XmlSchemaDatatype ไปเป็นประเภทเวลารันที่ระบุ
type: docs
weight: 66
url: /th/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) เมธอด


แปลงค่าที่ระบุซึ่งประเภทเป็นหนึ่งในการแสดงผลที่ถูกต้องของประเภทสคีม่า XML ที่แสดงโดย [XmlSchemaDatatype](../) ไปเป็นประเภทเวลารันที่ระบุ

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ค่าลูกอินพุตที่จะทำการแปลงเป็นประเภทที่ระบุ |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทเป้าหมายที่ต้องการแปลงค่าลูกอินพุตให้เป็น |

### ค่าที่คืนกลับ

ค่าที่แปลงแล้วของอินพุต

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด


แปลงค่าที่ระบุซึ่งประเภทเป็นหนึ่งในการแสดงผลที่ถูกต้องของประเภทสคีม่า XML ที่แสดงโดย [XmlSchemaDatatype](../) ไปเป็นประเภทเวลารันที่ระบุโดยใช้ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) หาก [XmlSchemaDatatype](../) แสดงประเภท **xs:QName** หรือประเภทที่สืบทอดมาจากมัน

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ค่าลูกอินพุตที่จะทำการแปลงเป็นประเภทที่ระบุ |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทเป้าหมายที่ต้องการแปลงค่าลูกอินพุตให้เป็น |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้สำหรับแก้ไขคำนำหน้าชื่อเนมสเปซ ใช้ได้เฉพาะเมื่อ [XmlSchemaDatatype](../) แสดงประเภท **xs:QName** หรือประเภทที่สืบทอดมาจากมัน |

### ค่าที่คืนกลับ

ค่าที่แปลงแล้วของอินพุต

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlSchemaDatatype](../)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)