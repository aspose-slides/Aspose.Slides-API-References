---
title: ValueAs()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คืนค่าของโหนดปัจจุบันในรูปแบบ Type ที่ระบุ โดยใช้วัตถุ IXmlNamespaceResolver ที่ระบุเพื่อแก้ไขคำนำหน้าพื้นที่ชื่อ
type: docs
weight: 378
url: /th/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

คืนค่าของโหนดปัจจุบันในรูปแบบ Type ที่ระบุ โดยใช้วัตถุ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าพื้นที่ชื่อ

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Type ที่ใช้เพื่อคืนค่าของโหนดปัจจุบัน |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | อ็อบเจกต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้เพื่อแก้ไขคำนำหน้าพื้นที่ชื่อ |

### ค่าที่ส่งคืน

ค่าของโหนดปัจจุบันในรูปแบบ Type ที่ร้องขอ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)