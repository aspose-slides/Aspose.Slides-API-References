---
title: ReadElementContentAs()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: อ่านข้อความขององค์ประกอบเป็นประเภทที่ต้องการ
type: docs
weight: 586
url: /th/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

อ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของค่าที่จะส่งกลับ |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | อ็อบเจ็กต์ [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) ที่ใช้ในการแก้ไขคำนำหน้าช่วงชื่อใด ๆ ที่เกี่ยวข้องกับการแปลงประเภท |

### ค่าที่ส่งกลับ

เนื้อหาองค์ประกอบที่แปลงเป็นอ็อบเจ็กต์ประเภทที่ร้องขอ

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) เมธอด

ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่ แล้วอ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของค่าที่จะส่งกลับ |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | อ็อบเจ็กต์ [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) ที่ใช้ในการแก้ไขคำนำหน้าช่วงชื่อใด ๆ ที่เกี่ยวข้องกับการแปลงประเภท |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบ |

### ค่าที่ส่งกลับ

เนื้อหาองค์ประกอบที่แปลงเป็นอ็อบเจ็กต์ประเภทที่ร้องขอ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* คลาส [XmlReader](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)