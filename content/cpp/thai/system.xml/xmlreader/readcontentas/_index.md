---
title: ReadContentAs()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านเนื้อหาเป็นอ็อบเจกต์ของประเภทที่ระบุ.
type: docs
weight: 456
url: /th/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

อ่านเนื้อหาเป็นอ็อบเจกต์ของประเภทที่ระบุ

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของค่าที่จะถูกส่งคืน |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | อ็อบเจกต์ [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) ที่ใช้ในการแก้ไขคำนำหน้าชื่อเนมสเปซใด ๆ ที่เกี่ยวข้องกับการแปลงประเภท ตัวอย่างเช่น สามารถใช้เมื่อต้องแปลงอ็อบเจกต์ [XmlQualifiedName](../../xmlqualifiedname/) เป็น **xs:string** ค่านี้สามารถเป็น **nullptr** |

### ค่าที่ส่งคืน

เนื้อหาข้อความที่ต่อกันหรือค่าคุณลักษณะที่แปลงเป็นประเภทที่ร้องขอ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)