---
title: ValueAs()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนค่าของรายการในรูปแบบประเภทที่ระบุ.
type: docs
weight: 131
url: /th/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) เมธอด

ส่งคืนค่าของรายการในรูปแบบประเภทที่ระบุ.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทที่ใช้เพื่อส่งคืนค่าของรายการ |

### ค่าที่ส่งคืน

ค่าของรายการในรูปแบบประเภทที่ร้องขอ.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

เมื่อถูกเขียนทับในคลาสที่สืบทอด จะส่งคืนค่าของรายการในรูปแบบประเภทที่ระบุโดยใช้วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าชื่อเนมสเปซ.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทที่ใช้เพื่อส่งคืนค่าของรายการ |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้เพื่อแก้ไขคำนำหน้าชื่อเนมสเปซ |

### ค่าที่ส่งคืน

ค่าของรายการในรูปแบบประเภทที่ร้องขอ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XPathItem](../)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)