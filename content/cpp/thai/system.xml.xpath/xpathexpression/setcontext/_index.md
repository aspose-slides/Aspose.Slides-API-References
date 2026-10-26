---
title: SetContext()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อทำการ override ในคลาสที่สืบทอด, ระบุอ็อบเจกต์ XmlNamespaceManager ที่ใช้สำหรับการแก้ไขเนมสเปซ.
type: docs
weight: 53
url: /th/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด, ระบุอ็อบเจกต์ [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) ที่ใช้สำหรับการแก้ไขเนมสเปซ.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | อ็อบเจกต์ [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) ที่ใช้สำหรับการแก้ไขเนมสเปซ. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด, ระบุอ็อบเจกต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้สำหรับการแก้ไขเนมสเปซ.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | อ็อบเจกต์ที่ทำการ Implement อินเทอร์เฟซ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) เพื่อใช้ในการแก้ไขเนมสเปซ. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Class [XPathExpression](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)